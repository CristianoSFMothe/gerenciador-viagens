<h1 align="center">Curso de API Rest</h1>

# O que é a API RESTful?

A API RESTful é uma interface que dois sistemas de computador usam para trocar informações de forma segura pela internet. A maioria das aplicações de negócios precisa se comunicar com outras aplicações internas e de terceiros para executar várias tarefas. Por exemplo, para gerar contracheques mensais, seu sistema interno de contas precisa compartilhar dados com o sistema bancário de seu cliente a fim de automatizar o faturamento e se comunicar com uma aplicação interna de planilha de horas. As APIs RESTful suportam essa troca de informações porque seguem padrões de comunicação de software seguro, confiáveis e eficientes.

## O que é uma API?

Uma interface de programação de aplicação (Representational State Transfer), define as regras que precisa seguir para se comunicar com outros sistemas de software. Os desenvolvedores expõem ou criam APIs para que outras aplicações possam se comunicar com as suas aplicações programaticamente

### Clientes

Clientes são usuários que desejam acessar informações da Web. O cliente pode ser uma pessoa ou um sistema de software que usa a API.

### Recursos

Recursos são as informações que diferentes aplicações fornecem aos seus clientes. Os recursos podem ser imagens, vídeos, textos, números ou qualquer tipo de dado. A máquina que fornece o recurso ao cliente também é chamada **servidor** (server)

## O que é REST?

A representational state transfer (REST – transferência de estado representacional) é uma arquitetura de software que impõe condições sobre como uma API deve funcionar. A REST foi criada inicialmente como uma diretriz para gerir a comunicação numa rede complexa como a internet. Pode usar a arquitetura baseada em REST para possibilitar a comunicação confiável e de alta performance em escala. Pode implementá-la e modificá-la facilmente, trazendo visibilidade e portabilidade entre plataformas para qualquer sistema de API.

Os desenvolvedores de **API** podem projetar **APIs** usando várias arquiteturas diferentes. As APIs que seguem o estilo de arquitetura REST são chamadas **APIs REST**. Os serviços da Web que implementam a arquitetura REST são chamados serviços da **Web RESTful**. O termo **API RESTful** geralmente se refere a APIs da Web RESTful. No entanto, pode usar os termos API REST e API RESTful de forma intercambiável

A interface uniforme impõe quatro restrições arquitetônicas:

1. As solicitações devem identificar recursos. Elas fazem isso usando um identificador de recurso uniforme.
2. Os clientes têm informações suficientes na representação do recurso para modificar ou excluir o recurso caso queiram. O servidor atende a essa condição enviando metadados que descrevem melhor o recurso.
3. Os clientes recebem informações sobre como processar ainda mais a representação. O servidor faz isso enviando mensagens autodescritivas que contêm metadados sobre como o cliente pode usá-los melhor.
4. Os clientes recebem informações sobre todos os outros recursos relacionados de que precisam para concluir uma tarefa. O servidor faz isso enviando hiperlinks na representação para que os clientes possam descobrir dinamicamente mais recursos.

### Interface uniforme

A interface uniforme é fundamental para o design de qualquer serviço da Web RESTful. Indica que o servidor transfere informações em formato-padrão. O recurso formatado é chamado representação em REST. Esse formato pode ser diferente da representação interna do recurso na aplicação do servidor.

### Ausência de estado

Na arquitetura REST, a ausência de estado refere-se a um método de comunicação onde o servidor completa cada solicitação do cliente independentemente de todas as solicitações anteriores. Os clientes podem solicitar recursos em qualquer ordem, e cada solicitação é sem estado ou isolada de outras solicitações. Essa restrição de design da API REST implica que o servidor possa entender completamente e atender à solicitação todas as vezes.

### Sistema em camadas

Numa arquitetura de sistema em camadas, o cliente pode se conectar a outros intermediários autorizados entre o cliente e o servidor e ainda receber respostas do servidor. Os servidores também podem passar solicitações para outros servidores. Pode projetar o seu serviço da **Web RESTful** para ser executado em vários servidores com diversas camadas, como:
* segurança, 
* aplicação
* lógica de negócios
Trabalhando juntos para atender às solicitações do cliente. Essas camadas permanecem invisíveis para o cliente.

### Capacidade de armazenamento

Os serviços da Web RESTful permite o armazenamento em cache, que é o processo de armazenar algumas respostas no cliente ou em um intermediário para melhorar o tempo de resposta do servidor.
Os serviços da Web RESTful controlam o cache usando respostas de API que se definem como armazenáveis ou não em cache.

### Código sob demanda

No estilo de arquitetura REST, os servidores podem estender ou personalizar temporariamente a funcionalidade do cliente, transferindo o código de programação de software para o cliente

## REST e RESTful são a mesma coisa?

Agora que já conheceu um pouco mais sobre o REST, está na hora de entender o que é RESTful. Embora possam gerar certa confusão, os dois termos revelam o mesmo propósito. Sendo assim, podemos dizer que sistemas que utilizam determinações REST são chamados de RESTful.

* **REST:** representa um apanhado de princípios de arquitetura,
* **RESTful:** representa a condição de um sistema específico em aplicar os conceitos de REST.





# Gerenciador de Viagens

> Este é um repositório para aprender um pouco mais sobre APIs REST.
> Nele existem vários problemas e más práticas para serem utilizadas como exemplo do que não fazer.


### Verificando API

> Inicialmente para verificar se a API está funcionando irá ser utilizado por linha de comandos

Para isso iremos utilizar o `CURL` como o seguinte comando

```bash
$ curl -X GET http://localhost:8089/api/v1/status

# Aplicação está funcionando corretamente
```
Se no terminal aparece a seguinte mensagem **Aplicação está funcionando corretamente** isso quer dizer que o serviço está disponivel 

# Swagger

## O que é Swagger?
Trata-se de uma aplicação open source que auxilia desenvolvedores nos processos de definir, criar, documentar e consumir APIs REST.  Em suma, o Swagger visa padronizar este tipo de integração, descrevendo os recursos que uma API deve possuir, como endpoints, dados recebidos, dados retornados, códigos HTTP e métodos de autenticação, entre outros.

## Abrindo o Swagger

Para acessar a página <a href="http://localhost:8089/api/swagger-ui.html" targe="blank">http://localhost:8089/api/swagger-ui.html</a> teremos acesso a página do **Swwager** com a documentação

![swagger.png](..%2F..%2F..%2F..%2FPictures%2Fposts%2Fswagger.png)

## Aunteticado via CURL

Para realizar uma request de autenticação via CURL com o seguinte comando:

```bash
$ curl -X POST http://localhost:8089/api/v1/auth -d '{ "email": "admin@email.com", "senha": "654321" }' -H 'Content-Type: application/json'
```
Onde:

* `-d` e de Data: que será enviando o corpo do bady do JSON
* `-h` que de Header: que irá ser informando o Header da aplicação

```bash
$ curl -X POST http://localhost:8089/api/v1/auth -d '{ "email": "admin@email.com", "senha": "654321" }' -H 'Content-Type: application/json'
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100   305    0   256  100    49   3318    635 --:--:-- --:--:-- --:--:--  3961{"data":{"token":"eyJhbGciOiJIUzUxMiJ9.eyJzdWIiOiJhZG1pbkBlbWFpbC5jb20iLCJyb2xlIjoiUk9MRV9BRE1JTiIsImNyZWF0ZWQiOjE2NzQ3NzQzNDM5NjEsImV4cCI6MTY3NDg3NDM0Mn0.QYRlSBvCMOJap2APPU3xqESDDilC6VxNS_jdRWLw5XygNuIqm45IW5pja32xlJbhxEKLWnyDIIbaL8SeNxIhxA"},"errors":[]} 
```

Mas esse comando só exibe o body que venho na resposta, para ver header usar o seguinte comando:

```bash
$ curl -X POST -i http://localhost:8089/api/v1/auth -d '{ "email": "admin@email.com", "senha": "654321" }' -H 'Content-Type: application/json'
```

Onde:

* `-i` traz a informação do header 

```bash
$ curl -X POST -i http://localhost:8089/api/v1/auth -d '{ "email": "admin@email.com", "senha": "654321" }' -H 'Content-Type: application/json'
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100   305    0   256  100    49   2681    513 --:--:-- --:--:-- --:--:--  3210HTTP/1.1 200
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
Cache-Control: no-cache, no-store, max-age=0, must-revalidate
Pragma: no-cache
Expires: 0
X-Frame-Options: DENY
Content-Type: application/json;charset=UTF-8
Transfer-Encoding: chunked
Date: Thu, 26 Jan 2023 23:22:32 GMT

{"data":{"token":"eyJhbGciOiJIUzUxMiJ9.eyJzdWIiOiJhZG1pbkBlbWFpbC5jb20iLCJyb2xlIjoiUk9MRV9BRE1JTiIsImNyZWF0ZWQiOjE2NzQ3NzUzNTI2OTcsImV4cCI6MTY3NDg3NTM1MX0.LbLqfopMBPUz_8iT98VKskgVBvMZuNtuvx6x8nCG4-u0_GM2pYe9LJofQ2E6fgKZDB2peV7OEdYHvCj6n2rDpg"},"errors":[]}

```

Para esconder o _time_ que exiber do tempo que levou para baixar a aplicação inserir o `-s` da seguinte forma:

```bash
$ curl -X POST -is http://localhost:8089/api/v1/auth -d '{ "email": "admin@email.com", "senha": "654321" }' -H 'Content-Type: application/json'
```





