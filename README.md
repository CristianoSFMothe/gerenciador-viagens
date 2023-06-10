<h1 align="center">Curso de API Rest</h1>

<div align="center">
    <img src="https://user-images.githubusercontent.com/68359459/215295002-8f34c792-9dad-4ddd-b5a8-62d90cd7c070.jpeg" alt="API RESTfull" />
</div>

<div align="center">
    <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/CristianoSFMothe/gerenciador-viagens">
    <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/CristianoSFMothe/gerenciador-viagens">
    <img alt="GitHub repo size" src="https://img.shields.io/github/repo-size/CristianoSFMothe/gerenciador-viagens">
    <img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-yellow.svg">  
    <br />
    <img alt="Spring" src="https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white">
    <img alt="IntelliJ IDE" src="https://img.shields.io/badge/IntelliJIDEA-000000.svg?style=for-the-badge&logo=intellij-idea&logoColor=white">
    <img alt="Java" src="https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=java&logoColor=white">
    <img alt="Apache Maven" src="https://img.shields.io/badge/Apache%20Maven-C71A36?style=for-the-badge&logo=Apache%20Maven&logoColor=white">
    <img alt="Testing-Library" src="https://img.shields.io/badge/-TestingLibrary-%23E33332?style=for-the-badge&logo=testing-library&logoColor=white">
</div>



## :boy: About me

<a href="https://github.com/CristiaDaSilvaFerreira" alt="github" target="_blank"><img height="32" src="https://img.shields.io/badge/GitHub-000000?&style=flat-square&logo=GitHub&logoColor=white"></a> <a href="https://www.linkedin.com/in/cristiano-da-silva-ferreira" alt="linkedin" target="_blank"> <img height="32" src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?&style=flat-square&logo=linkedin&logoColor=white"></a> 

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

---
# Quais são os benefícios das APIs RESTful?

APIs RESTful incluem os seguintes benefícios:

* **Escalabilidade:** Os sistemas que implementam APIs REST podem ser escalados com eficiência, porque a REST otimiza as interações entre cliente e servidor
* **Flexibilidade:** Os serviços da Web RESTful permitem a separação total do cliente do servidor. Eles simplificam e desacoplam vários componentes do servidor para que cada parte possa evoluir independentemente. Mudanças de plataforma ou tecnologia na aplicação do servidor não afetam a aplicação do cliente. A capacidade de camadas de funções de aplicações aumenta a flexibilidade.
* **Independência:** APIs REST são independentes da tecnologia usada. Você pode escrever aplicações de cliente e servidor em várias linguagens de programação sem afetar o design da API. Também é possível alterar a tecnologia subjacente em ambos os lados sem afetar a comunicação.

---

# Como funcionam as APIs RESTful?

![API-page-graphic](https://user-images.githubusercontent.com/68359459/215295017-9123c69a-1d31-4e4a-bb0d-171ddd32939d.png)


A função básica de uma API RESTful é a mesma de navegar na internet. O cliente entra em contato com o servidor usando a API quando requer um recurso. Os desenvolvedores de API explicam como o cliente deve usar API REST na documentação da API da aplicação do servidor. Estas são as etapas gerais para qualquer chamada de API REST:

1. O cliente envia uma solicitação ao servidor. O cliente segue a documentação da API para formatar a solicitação de modo que o servidor entenda.
2. O servidor autentica o cliente e confirma que o cliente tem o direito de fazer essa solicitação.
3. O servidor recebe a solicitação e a processa internamente.
4. O servidor retorna uma resposta ao cliente. A resposta contém informações que indicam ao cliente se a solicitação foi bem-sucedida. A resposta também inclui informações solicitadas pelo cliente.

Os detalhes de solicitação e resposta da API REST variam um pouco, dependendo de como os desenvolvedores da API projetam a API.

---

# O que contém a solicitação do cliente da API RESTful?

As APIs RESTful exigem que as solicitações contenham os seguintes componentes principais:

## Identificador de recurso exclusivo

O servidor identifica cada recurso com identificadores de recursos exclusivos. Para serviços REST, o servidor normalmente realiza a identificação de recursos usando um **_uniform resource locator_** (URL – localizador de recurso uniforme). O URL especifica o caminho para o recurso.
O URL também é chamado **endpoint** de solicitação e específica ao servidor o que o cliente requer.

## Método

Os desenvolvedores geralmente implementam APIs RESTful usando o **_Hypertext Transfer Protocol_** (Protocolo de Transferência de Hipertexto). Um método HTTP informa ao servidor o que ele precisa fazer com o recurso.

* **GET:** Os clientes usam GET para acessar recursos localizados no URL especificado no servidor. Eles podem armazenar em cache solicitações GET e enviar parâmetros na solicitação da API RESTful para instruir o servidor a filtrar dados antes de enviar.
* **POST:** Os clientes usam POST para enviar dados ao servidor. Eles incluem a representação de dados com a solicitação. Se enviarem a mesma solicitação POST várias vezes, criarão o mesmo recurso várias vezes.
* **PUT:** Os clientes usam PUT para atualizar recursos existentes no servidor. Ao contrário do POST, o envio da mesma solicitação PUT várias vezes em um serviço da Web RESTful tem o mesmo resultado.
* **DELETE:** Os clientes usam a solicitação DELETE para remover o recurso. Uma solicitação DELETE pode alterar o estado do servidor. No entanto, se o usuário não tiver a autenticação apropriada, a solicitação falhará.

## Cabeçalhos HTTP

Os cabeçalhos de solicitação são os metadados trocados entre o cliente e o servidor. Por exemplo, o cabeçalho da solicitação indica o formato da solicitação e da resposta, fornece informações sobre o **status** da solicitação e assim por diante.

* **Dados:** As solicitações da API REST podem incluir dados para POST, PUT e outros métodos HTTP para funcionarem com êxito.

* **Parâmetros:** As solicitações da API RESTful podem incluir parâmetros que fornecem ao servidor mais detalhes sobre o que precisa ser feito. A seguir, estão alguns tipos diferentes de parâmetro.

1. Parâmetros de caminho que especificam detalhes do URL.
2. Parâmetros de consulta que solicitam mais informações sobre o recurso.
3. Parâmetros de cookies que autenticam clientes rapidamente.

---

# O que são métodos de autenticação da API RESTful?

Um serviço da Web RESTful deve autenticar solicitações antes de enviar uma resposta. Autenticação é o processo de verificação de uma identidade.

As autenticações mais comuns da API RESTful são:

## Autenticação de HTTP

![api-identity-pt](https://user-images.githubusercontent.com/68359459/215295029-7e868b06-8fb4-4ae9-b31e-749edf1a7811.png)

O HTTP define alguns esquemas de autenticação que pode usar diretamente ao implementar a API REST. Estes são dois desses esquemas:

* **Autenticação básica:** Na autenticação básica, o cliente envia o nome de usuário e a senha no cabeçalho da solicitação. Ele os codifica com base64, que é uma técnica de codificação que converte o par em um conjunto de 64 caracteres para transmissão segura.

* **Autenticação do portador:** O termo autenticação do portador se refere ao processo de dar controle de acesso ao portador do token. O token do portador é normalmente uma cadeia de caracteres criptografada que o servidor gera em resposta a uma solicitação de login. O cliente envia o token nos cabeçalhos de solicitação para acessar recursos.

## Chaves de API
As chaves de API são outra opção para autenticação da API REST. Nessa abordagem, o servidor atribui um valor gerado exclusivo a um cliente iniciante. Sempre que o cliente tenta acessar recursos, ele usa a chave de API exclusiva para verificar a si mesmo. As chaves de API são menos seguras porque o cliente precisa transmitir a chave, o que a torna vulnerável a roubo de rede.

## OAuth
OAuth combina senhas e tokens para acesso de login altamente seguro a qualquer sistema. Primeiro, o servidor solicita uma senha e, depois, um token adicional para concluir o processo de autorização. Ele pode verificar o token a qualquer momento e também ao longo do tempo com escopo e longevidade específicos.

---

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

---

# Swagger

## O que é Swagger?
Trata-se de uma aplicação open source que auxilia desenvolvedores nos processos de definir, criar, documentar e consumir APIs REST.  Em suma, o Swagger visa padronizar este tipo de integração, descrevendo os recursos que uma API deve possuir, como endpoints, dados recebidos, dados retornados, códigos HTTP e métodos de autenticação, entre outros.

## Abrindo o Swagger

Para acessar a página <a href="http://localhost:8089/api/swagger-ui.html" targe="blank">http://localhost:8089/api/swagger-ui.html</a> teremos acesso a página do **Swwager** com a documentação

![swagger-viagem](https://user-images.githubusercontent.com/68359459/215295074-da3eee84-f638-4e3f-a7da-0b10480a0c60.jpg)

--- 

# O que é o curl?

É uma ferramenta para transferir dados de/para um servidor, usando um dos protocolos suportados. Normalmente, usamos o HTTP, mas as opções são muitas, de **FTP** e **GOPHER** a **IMAP** e **LDAP**.

* **FTP:** _File Transfer Protocol_ Em português, ele traduz-se como **Protocolo de Transferência de Arquivos**,  é um protocolo usado para transferir arquivos por uma rede de computadores, desde uma local à internet. Basicamente, permite a troca de arquivos entre dois computadores de modo direto, em que um ganha acesso às pastas do outro.
  O protocolo é o meio mais antigo de transferir dados entre computadores de uma rede, tendo surgido em 1971 e usa o modelo cliente/servidor, onde o primeiro faz o acesso aos dados e o segundo os armazena.
* **GOPHER:** é um método de comunicação desenhado para distribuir e procurar documentos na Internet. Esse processo permitiu que arquivos armazenados em servidores fossem acessados remotamente a partir de outros lugares. Este protocolo foi utilizado na Internet antes da web se tornar popular. Geralmente, o Gopher é um modelo somente em texto, sem imagens ou conteúdo multimídia, além de não permitir scripts.
* **IMAP:** permite que acesse o seu email onde quer que esteja, de qualquer dispositivo. Ao ler uma mensagem de email usando o IMAP, não está realmente baixando ou armazenando-a no seu computador. Em vez disso, você está lendo-o do serviço de email. Como resultado, pode verificar o seu email de diferentes dispositivos, em qualquer lugar do mundo: seu telefone, um computador, um computador amigo.
* **LDAP:** _Lightweight Directory Access Protocol_ é um protocolo que ajuda os usuários a localizar dados sobre organizações, pessoas e muito mais. O LDAP tem dois objetivos centrais: armazenar dados no diretório LDAP e autenticar o acesso de usuários a ele. Ele também oferece a linguagem de comunicação que as aplicações exigem para enviar e receber informações de serviços de diretório. Um serviço de diretório oferece acesso à localização das informações sobre organizações, indivíduos e outros dados em uma rede.

O **cURL** é uma ferramenta de linha de comando que funciona como interface para a biblioteca que faz o serviço pesado, o libcurl.
De forma geral, o seu navegador realiza requisições web, recebe respostas, lê/escreve cookies e renderiza a sua página.
Ele oferece uma infinidade de funções úteis como realização de autenticação, interação com API's, preencher formulários HTML, download de arquivos e páginas HTML, etc.

## Instalando: como ativar o cURL

### No Linux

* Para instalar, se for usuário de **GNU/Linux** e usar distribuições baseadas em Debian (como o Ubuntu), basta executar:

```bash
sudo apt install curl
```

* Para distros baseadas em Arch Linux execute:

```bash
sudo pacman -S curl
```

### No macOS

* Há alguns anos o macOS já vem com o curl instalado. Execute curl --version para verificar.

```bash
brew install curl
```

### No Windows

As últimas versões do Windows também já estão vindo com o curl por padrão. Mas pode baixar um <a href="http://www.confusedbycode.com/curl/" target="blank">instalador gráfico</a>. Após isso, o **cURL** deve estar em seu PATH e pronto para usar pelo **CMD** ou **PowerShell**.

## Aunteticado via CURL

Para realizar uma autentição, temos que enviar o seguinte body:

```json
{
  "email": "string",
  "senha": "string"
}
```

Para realizar uma request de autenticação via CURL com o seguinte comando:

```bash
$ curl -X POST http://localhost:8089/api/v1/auth -d '{ "email": "admin@email.com", "senha": "654321" }' -H 'Content-Type: application/json'
```

Nesse casa recebemos esse JSON

```json
{
  "data": {
    "token": "eyJhbGciOiJIUzUxMiJ9.eyJzdWIiOiJhZG1pbkBlbWFpbC5jb20iLCJyb2xlIjoiUk9MRV9BRE1JTiIsImNyZWF0ZWQiOjE2NzQ5NDkxNzUzNjcsImV4cCI6MTY3NTA0OTE3NH0.nn-_XJ_jfMOSDkxZgp_pM4QvlCDcznOiLnqsVNNUgkCnLLK7BEDTktbXHEktLUFKz7nDZ3dMxjCUU6aPVkf9VQ"
  },
  "errors": []
}
```
Onde:

* `-d`, --bady	Dados a serem enviados no POST
* `-H`, --header	Envia o header da requisição
* `-X`, --request	Especifica o método HTTP a ser usado na requisição


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

* `-i`, --include	Mostra o header da resposta no output

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
HTTP/1.1 200
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
Cache-Control: no-cache, no-store, max-age=0, must-revalidate
Pragma: no-cache
Expires: 0
X-Frame-Options: DENY
Content-Type: application/json;charset=UTF-8
Transfer-Encoding: chunked
Date: Sat, 28 Jan 2023 23:14:37 GMT

{"data":{"token":"eyJhbGciOiJIUzUxMiJ9.eyJzdWIiOiJhZG1pbkBlbWFpbC5jb20iLCJyb2xlIjoiUk9MRV9BRE1JTiIsImNyZWF0ZWQiOjE2NzQ5NDc2Nzc5ODUsImV4cCI6MTY3NTA0NzY3Nn0.y_fftMO0nu5uZOVWpNfF22rrhY2TeZcFmNpeXdxl1B3M1EMx2bvr9PlezVzUBxbZi79qAHNy891XUKIp7narOA"},"errors":[]}

```

## Cadastrar uma viagem via CURL

* Como usuário administrador

Para realizar o cadastro de uma viagem, olhando no Swagger podemos observar que teremos que enviar esse JSON

```json
{
  "acompanhante": "string",
  "dataPartida": "string",
  "dataRetorno": "string",
  "localDeDestino": "string",
  "regiao": "string"
}
```

> OBS.: Estanto primeiramente autorizado na API

Estando autenticado na aplicação como um administrado, pode-se agora cadastrar uma viagem, como o comando:

```bash
$ curl -X POST -is http://localhost:8089/api/v1/viagens -d '{ "acompanhante": "Aline", "dataPartida": "2023-01-28", "dataRetorno": "2023-02-28", "localDeDestino": "Santa Catarina", "regiao": "Sul"  }' -H 'Content-Type: application/json' -H 'Authorization: eyJhbGciOiJIUzUxMiJ9.eyJzdWIiOiJhZG1pbkBlbWFpbC5jb20iLCJyb2xlIjoiUk9MRV9BRE1JTiIsImNyZWF0ZWQiOjE2NzQ5NDg0MTM1OTYsImV4cCI6MTY3NTA0ODQxMn0.tE8GY8AvGapWZL7Q9vwf2NH9YIlAsxou4klQJsGKVG_BFm4iBEY4zG-n1qOfEbzleCjEHZ5zU5DQlFNKcYbOnw'
```

Onde iremos obter a seguinte resposta:

```bash
HTTP/1.1 201
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
Cache-Control: no-cache, no-store, max-age=0, must-revalidate
Pragma: no-cache
Expires: 0
X-Frame-Options: DENY
Location: http://localhost:8089/api/v1/viagens/1
Content-Type: application/json;charset=UTF-8
Transfer-Encoding: chunked
Date: Sat, 28 Jan 2023 23:29:21 GMT

{"data":{"id":1,"localDeDestino":"Santa Catarina","dataPartida":"2023-01-28","dataRetorno":"2023-02-28","acompanhante":"Aline","regiao":"Sul"},"errors":[]}
```

Recebendo esse JSON como response

```json
{
  "data": {
    "id": 1,
    "localDeDestino": "Santa Catarina",
    "dataPartida": "2023-01-28",
    "dataRetorno": "2023-02-28",
    "acompanhante": "Aline",
    "regiao": "Sul"
  },
  "errors": []
}
```

Caso não informe o Token como no comando abaixo

```bash
$ curl -X POST -is http://localhost:8089/api/v1/viagens -d '{ "acompanhante": "Aline", "dataPartida": "2023-01-28", "dataRetorno": "2023-02-28", "localDeDestino": "Santa Catarina", "regiao": "Sul"  }' -H 'Content-Type: application/json' -H 'Authorization: '
```

```bash
HTTP/1.1 401
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
Cache-Control: no-cache, no-store, max-age=0, must-revalidate
Pragma: no-cache
Expires: 0
X-Frame-Options: DENY
Content-Type: application/json;charset=UTF-8
Transfer-Encoding: chunked
Date: Sat, 28 Jan 2023 23:48:59 GMT

{"timestamp":"2023-01-28T23:48:59.085+0000","status":401,"error":"Unauthorized","message":"Acesso negado. Você deve estar autenticado no sistema para acessar a URL solicitada.","path":"/api/v1/viagens"}
```
Recebemos o **status code** 401 que quer dizer **Unauthorized**, ou seja, a requisição foi enviada, mas não foi autorizada

```json
{
  "timestamp": "2023-01-28T23:48:59.085+0000",
  "status": 401,
  "error": "Unauthorized",
  "message": "Acesso negado. Você deve estar autenticado no sistema para acessar a URL solicitada.",
  "path": "/api/v1/viagens"
}
```
* Com usuário comum

Realizando o login como usuário comum atráves do CURL com o seguinte comando:

```bash
$ curl -X POST -is http://localhost:8089/api/v1/auth -d '{ "email": "usuario@email.com", "senha": "123456" }' -H 'Content-Type: application/json'
```
Recebemos essa resposta

```bash
HTTP/1.1 200
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
Cache-Control: no-cache, no-store, max-age=0, must-revalidate
Pragma: no-cache
Expires: 0
X-Frame-Options: DENY
Content-Type: application/json;charset=UTF-8
Transfer-Encoding: chunked
Date: Sat, 28 Jan 2023 23:58:15 GMT

{"data":{"token":"eyJhbGciOiJIUzUxMiJ9.eyJzdWIiOiJ1c3VhcmlvQGVtYWlsLmNvbSIsInJvbGUiOiJST0xFX1VTVUFSSU8iLCJjcmVhdGVkIjoxNjc0OTUwMjk1NDgwLCJleHAiOjE2NzUwNTAyOTR9.nb7D18mXpZNRxyaxX1BnSS3thOR1oqLrIVEPa6SUDn5RVIZMM_y8strrT8DuIgan7SQEfsyepNL7-RCnF5s2uQ"},"errors":[]}
```

```json
{
  "data": {
    "token": "eyJhbGciOiJIUzUxMiJ9.eyJzdWIiOiJ1c3VhcmlvQGVtYWlsLmNvbSIsInJvbGUiOiJST0xFX1VTVUFSSU8iLCJjcmVhdGVkIjoxNjc0OTUwMjk1NDgwLCJleHAiOjE2NzUwNTAyOTR9.nb7D18mXpZNRxyaxX1BnSS3thOR1oqLrIVEPa6SUDn5RVIZMM_y8strrT8DuIgan7SQEfsyepNL7-RCnF5s2uQ"
  },
  "errors": []
}
```
Enviando novamente a requisição para cadastrar uma viagem, mas dessa vez como usuário comum

```bash
$ curl -X POST -is http://localhost:8089/api/v1/viagens -d '{ "acompanhante": "Aline", "dataPartida": "2023-01-28", "dataRetorno": "2023-02-28", "localDeDestino": "Santa Catarina", "regiao": "Sul"  }' -H 'Content-Type: application/json' -H 'Authorization: eyJhbGciOiJIUzUxMiJ9.eyJzdWIiOiJ1c3VhcmlvQGVtYWlsLmNvbSIsInJvbGUiOiJST0xFX1VTVUFSSU8iLCJjcmVhdGVkIjoxNjc0OTUwMjk1NDgwLCJleHAiOjE2NzUwNTAyOTR9.nb7D18mXpZNRxyaxX1BnSS3thOR1oqLrIVEPa6SUDn5RVIZMM_y8strrT8DuIgan7SQEfsyepNL7-RCnF5s2uQ'
```

```bash
HTTP/1.1 403
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
Cache-Control: no-cache, no-store, max-age=0, must-revalidate
Pragma: no-cache
Expires: 0
X-Frame-Options: DENY
Content-Type: application/json;charset=UTF-8
Transfer-Encoding: chunked
Date: Sun, 29 Jan 2023 00:01:25 GMT

{"timestamp":"2023-01-29T00:01:25.703+0000","status":403,"error":"Forbidden","exception":"org.springframework.security.access.AccessDeniedException","message":"Acesso negado","path":"/api/v1/viagens"}
```

Observando o JSON podemos ver que recebemos o **status code** **403 Forbidden**  indica que o servidor entendeu o pedido, mas se recusa a autorizá-lo.

```json
{
  "timestamp": "2023-01-29T00:01:25.703+0000",
  "status": 403,
  "error": "Forbidden",
  "exception": "org.springframework.security.access.AccessDeniedException",
  "message": "Acesso negado",
  "path": "/api/v1/viagens"
}
```
# Consultando os dados - GET

Para consulta todas a viagens cadastradas, realiza-se **GET** via CURL, é necessário fazer isso com o **usuário comum**, para pode logar com ele com o comando:

```bash
$ curl -X POST -is http://localhost:8089/api/v1/auth -d '{ "email": "usuario@email.com", "senha": "123456" }' -H 'Content-Type: application/json'
```

```bash
HTTP/1.1 200
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
Cache-Control: no-cache, no-store, max-age=0, must-revalidate
Pragma: no-cache
Expires: 0
X-Frame-Options: DENY
Content-Type: application/json;charset=UTF-8
Transfer-Encoding: chunked
Date: Sun, 29 Jan 2023 01:35:11 GMT

{"data":{"token":"eyJhbGciOiJIUzUxMiJ9.eyJzdWIiOiJ1c3VhcmlvQGVtYWlsLmNvbSIsInJvbGUiOiJST0xFX1VTVUFSSU8iLCJjcmVhdGVkIjoxNjc0OTU2MTExNTU0LCJleHAiOjE2NzUwNTYxMTB9.ltTrvj1fr8pGHqMXo-U-njeKVjH0jxC3U6wvTpZHNJpEp2frvrt0MZ6UENYvPum1BNws1DW1fBvuOP-5avzMog"},"errors":[]}
```

```json
{
  "data": {
    "token": "eyJhbGciOiJIUzUxMiJ9.eyJzdWIiOiJ1c3VhcmlvQGVtYWlsLmNvbSIsInJvbGUiOiJST0xFX1VTVUFSSU8iLCJjcmVhdGVkIjoxNjc0OTU2MTExNTU0LCJleHAiOjE2NzUwNTYxMTB9.ltTrvj1fr8pGHqMXo-U-njeKVjH0jxC3U6wvTpZHNJpEp2frvrt0MZ6UENYvPum1BNws1DW1fBvuOP-5avzMog"
  },
  "errors": []
}
```

Tento o token do usuário atráves da autenticação realizada, poder ser usar o entpoit de consulta das viagens cadastradas

```bash
$ curl -X GET -is http://localhost:8089/api/v1/viagens -H 'Authorization: eyJhbGciOiJIUzUxMiJ9.eyJzdWIiOiJ1c3VhcmlvQGVtYWlsLmNvbSIsInJvbGUiOiJST0xFX1VTVUFSSU8iLCJjcmVhdGVkIjoxNjc0OTU2MTExNTU0LCJleHAiOjE2NzUwNTYxMTB9.ltTrvj1fr8pGHqMXo-U-njeKVjH0jxC3U6wvTpZHNJpEp2frvrt0MZ6UENYvPum1BNws1DW1fBvuOP-5avzMog'
```
Recebendo essa resposta no terminal

```bash
HTTP/1.1 200
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
Cache-Control: no-cache, no-store, max-age=0, must-revalidate
Pragma: no-cache
Expires: 0
X-Frame-Options: DENY
Content-Type: application/json;charset=UTF-8
Transfer-Encoding: chunked
Date: Sun, 29 Jan 2023 01:38:26 GMT

{"data":[{"id":1,"localDeDestino":"Santa Catarina","dataPartida":"2023-01-28","dataRetorno":"2023-02-28","acompanhante":"Aline","regiao":"Sul"}],"errors":[]}
```
Pode-se ver que receber esse JSON

```json
{
  "data": [
    {
      "id": 1,
      "localDeDestino": "Santa Catarina",
      "dataPartida": "2023-01-28",
      "dataRetorno": "2023-02-28",
      "acompanhante": "Aline",
      "regiao": "Sul"
    },
    {
      "id": 2,
      "localDeDestino": "Manaus",
      "dataPartida": "2023-01-28",
      "dataRetorno": "2023-02-28",
      "acompanhante": "Aline",
      "regiao": "Norte"
    }
  ],
  "errors": []
}
```

Também pode consultar as viagens passando por parâmetro via query uma informação, nesse caso seria a região, nesse caso o comando via CURL ficará da seguinte forma

```bash
$ curl -X GET -is http://localhost:8089/api/v1/viagens?regiao=Sul -H 'Authorization: eyJhbGciOiJIUzUxMiJ9.eyJzdWIiOiJ1c3VhcmlvQGVtYWlsLmNvbSIsInJvbGUiOiJST0xFX1VTVUFSSU8iLCJjcmVhdGVkIjoxNjc0OTU2MTExNTU0LCJleHAiOjE2NzUwNTYxMTB9.ltTrvj1fr8pGHqMXo-U-njeKVjH0jxC3U6wvTpZHNJpEp2frvrt0MZ6UENYvPum1BNws1DW1fBvuOP-5avzMog'
```

Para cunsulta uma única viagens, passa-se o ID via **path**, usa-se o comando 

```bash
curl -X GET -is http://localhost:8089/api/v1/viagens/2 -H 'Authorization: eyJhbGciOiJIUzUxMiJ9.eyJzdWIiOiJ1c3VhcmlvQGVtYWlsLmNvbSIsInJvbGUiOiJST0xFX1VTVUFSSU8iLCJjcmVhdGVkIjoxNjc1MDAwODI5NTY3LCJleHAiOjE2NzUxMDA4Mjh9._t8pwwB9Vpv1o1UKUmIFrIsGkX5lR00lthhGXadJ-djqdf-eomOlZVrSS6wm8zViJCMfg-RRtxNv7xPF-nqhdw'
```

```bash
$ curl -X GET -is http://localhost:8089/api/v1/viagens/2 -H 'Authorization: eyJhbGciOiJIUzUxMiJ9.eyJzdWIiOiJ1c3VhcmlvQGVtYWlsLmNvbSIsInJvbGUiOiJST0xFX1VTVUFSSU8iLCJjcmVhdGVkIjoxNjc1MDAwODI5NTY3LCJleHAiOjE2NzUxMDA4Mjh9._t8pwwB9Vpv1o1UKUmIFrIsGkX5lR00lthhGXadJ-djqdf-eomOlZVrSS6wm8zViJCMfg-RRtxNv7xPF-nqhdw'

# Body da requisição
HTTP/1.1 200
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
Cache-Control: no-cache, no-store, max-age=0, must-revalidate
Pragma: no-cache
Expires: 0
X-Frame-Options: DENY
Content-Type: application/json;charset=UTF-8
Transfer-Encoding: chunked
Date: Sun, 29 Jan 2023 14:01:31 GMT

{"data":{"id":2,"localDeDestino":"Manaus","dataPartida":"2023-01-28","dataRetorno":"2023-02-28","acompanhante":"Aline","regiao":"Norte","temperatura":39.46},"errors":[]}
```

Recebendo esse JSON na requisição

```json
{
  "data": {
    "id": 2,
    "localDeDestino": "Manaus",
    "dataPartida": "2023-01-28",
    "dataRetorno": "2023-02-28",
    "acompanhante": "Aline",
    "regiao": "Norte",
    "temperatura": 39.46
  },
  "errors": []
}
```

---

# Insomnia Rest

Outra forma de podemos testar a nossa API e usando uma ferramenta gráfica, nesse caso iremos utilizar inicialmente o <a href="https://insomnia.rest/" target="blank">Insomnia</a>

![insomnia](https://user-images.githubusercontent.com/68359459/215357833-346efb59-258e-467a-9fb6-8eac4872d215.jpg)

## Autenticando usuário

> Autenticação do usuário com privilégio comum

* Informando o body da request obtida no Swagger

```json
{
  "email": "string",
  "senha": "string"
}
```

* Antes de tudo, podemos configura no **Insomnia** a nossa **URL** base

<img width="960" alt="insomnia1" src="https://user-images.githubusercontent.com/68359459/215357945-db6c3366-0ec6-4ab5-a2fa-1f4ea9effff0.png">

---

![insomnia2](https://user-images.githubusercontent.com/68359459/215357960-190819ac-1a3f-4895-aa87-d209f35501f1.jpg)


```json
{
	"servidor": "http://localhost:8089/api"
}
```

* Assim ou executar obtemos facilmente o token do usuário de forma visual, em que melhora e muito a leitura e o entendimento, além de ganho na produção

![insomnia3](https://user-images.githubusercontent.com/68359459/215357980-3693b1c8-4fc8-4df4-b15d-c3d3d5e067d7.jpg)

![insomnia-headers](https://user-images.githubusercontent.com/68359459/215358033-418c9bb8-15ec-44cd-8edd-2cae871b39de.jpg)

## Consultando todas as viagens cadastradas 

1. Primeiramente temos que inserir um novo endpoint do tipo **GET**

<img width="958" alt="inserir-new-request-get" src="https://user-images.githubusercontent.com/68359459/215358052-534f0c8c-2e50-4aa8-ac52-9bd5a79ff4a1.png">

![insomnia-get](https://user-images.githubusercontent.com/68359459/215358067-fd6b9338-8d31-4e78-844d-78766db5a3e4.jpg)

2. Criando a **Environment** (variável de ambiente) do token

![insomnia-var-token-user](https://user-images.githubusercontent.com/68359459/215358075-212de018-c555-4368-83e3-07cfe8b932b5.jpg)

Porém, esse recurso não e muito bem aplicado no casso dessa API, pois toda vez que fazer uma request de autenticação, irá gerar um novo token, podemos solucionar esse problema da seguinte forma, ao invés de usar o token com uma variável, podemos usar um recurso do próprio Insomnia nos disponibilizar
Que é capturando o atributo de outra requisição

<img width="961" alt="insomnia-bady-attribute" src="https://user-images.githubusercontent.com/68359459/215358081-8ae3f3c4-5b08-4a11-8de2-de90353d32a0.png">

* Configurando o response body attribute

  * Informa qual o **Request** que quer captura o dado
  * Criar o filtro do dado há ser capturado
  * Verificar que foi obtido o token com sucesso

<img width="961" alt="insomnia-config-attribute-response-body" src="https://user-images.githubusercontent.com/68359459/215358153-336c785b-356d-4a0f-8b78-763501743fb9.png">

3. Podendo assim facilmente configura as outras requisições do tipo GET

* Por ID de viagem

![insomnia-get-one](https://user-images.githubusercontent.com/68359459/215358176-282dc8df-0f10-4779-9ea0-2f1ea4c4b57e.jpg)

* Por paramêtro de região 

![insomnia-get-parament](https://user-images.githubusercontent.com/68359459/215358185-aabd5059-5b1f-47d0-a401-e2dc62e590b9.jpg)

## Cadastrar outras viagens

* Informa o body da requisição

```json
{
  "acompanhante": "Maria Inez",
  "dataPartida": "2023-30-01",
  "dataRetorno": "2023-28-02",
  "localDeDestino": "Porto Alegre",
  "regiao": "Sul"
}
```

* Executar o endpoint

![insomina-post-forbidden](https://user-images.githubusercontent.com/68359459/215358215-893dc5bc-af93-44dd-9e12-5aadfde51806.jpg)

Obtemos um **404 - Forbidden** de acesso negado, pois estamos há cadastrar uma viagem com o token do usuário com previlegios de usuário comum, onde não é permitido cadastra uma viagem

1. Realizando um POST com os dados do administrado, obtemos o seu token

```json
{
  "email": "admin@email.com",
  "senha": "654321"
}
```

2. Alterando no **Response => Body Attibute** a requisição que desejamos captura o token

<img width="960" alt="insomnia-alter-attribute-request" src="https://user-images.githubusercontent.com/68359459/215358233-3c1ca063-ba85-48b4-bf01-bdcbda476a1b.png">

![insomnia-post-admin](https://user-images.githubusercontent.com/68359459/215358246-067e014a-4490-4e81-847c-59ec9558a4d5.jpg)

---

# Postman

Podemos também utilizar o <a href="https://www.postman.com/downloads/" target="blank">Postman</a> para testa as nossas APIs, é uma ferrametna grafica assim como **Insomnnia**, que usamos anteriormente.

![postman.jpg](..%2F..%2F..%2F..%2FPictures%2FScreenshots%2Fpostman.jpg)

## Criando uma Collection

1. Clicar no botão para criar uma nova collection

![postman-home.png](..%2F..%2F..%2F..%2FPictures%2FScreenshots%2Fpostman-home.png)

2. Criar uma requisição do tipo POST

![postman-home-add-request.png](..%2F..%2F..%2F..%2FPictures%2FScreenshots%2Fpostman-home-add-request.png)

3. Executar o endpoint

![postman-login-admin.jpg](..%2F..%2F..%2F..%2FPictures%2FScreenshots%2Fpostman-login-admin.jpg)

Podemos ver que recebemos o mesmo JSON como resposta que tinhamos no **Insomnia** 

4. Também pode-ser criado variáveis

![postman-criar-var.png](..%2F..%2F..%2F..%2FPictures%2FScreenshots%2Fpostman-criar-var.png)

## Cadastrar uma viagem

1. Podendo também criar uma variável para a captura dinâmica do token

![postman-criar-token-var.jpg](..%2F..%2F..%2F..%2FPictures%2FScreenshots%2Fpostman-criar-token-var.jpg)

* Clica em **Tests**
  * Set a global variable
  
```javascript
const resposta = pm.response.json();
pm.globals.set("tokenAdmin", resposta.data.token);
```

2. Agora pode-se cadastrar viagens

![postman-cadastrar-viagem.jpg](..%2F..%2F..%2F..%2FPictures%2FScreenshots%2Fpostman-cadastrar-viagem.jpg)

3. No **Postman** podemos também criar uma validação do **Status Code**, criando um teste

![postman-status-code-test.jpg](..%2F..%2F..%2F..%2FPictures%2FScreenshots%2Fpostman-status-code-test.jpg)
