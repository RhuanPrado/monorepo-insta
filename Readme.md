# Projeto de Rede Social Simples com Next.js e Golang

Este é um projeto de uma aplicação de rede social simples desenvolvida com Next.js para o frontend e Golang (utilizando o framework Fiber) para o backend. O banco de dados utilizado é o MongoDB. O propósito deste projeto é demonstrar minhas habilidades de desenvolvimento web.

## Como Rodar o Projeto

### Pré-requisitos

Antes de começar, certifique-se de ter o Docker e o Docker Compose instalados em sua máquina.

### Passo 1: Navegue até o diretório

Navegue até o diretório /etc do projeto

### Passo 2: Inicie o Projeto com Docker Compose

Use o Docker Compose para construir e iniciar os contêineres do frontend, backend e banco de dados:

```bash
docker-compose up --build
```

Isso irá construir as imagens Docker e iniciar os serviços. Aguarde até que todos os serviços estejam em execução.

### Passo 3: Acesse a Aplicação

Após a conclusão dos passos anteriores, a aplicação deve estar em execução. Você pode acessá-la em seu navegador em:

```url
http://localhost:3000
```

## Funcionalidades Principais

- **Cadastro e Login**: Os usuários podem se cadastrar e fazer login na aplicação.

- **Feed Básico**: Os usuários podem visualizar um feed básico com postagens de outros usuários.

- **Adicionar Amigos**: Os usuários podem adicionar outros usuários como amigos.

- **Excluir Conta**: Os usuários têm a opção de excluir suas próprias contas.

- **Explorar Usuários**: Os usuários podem explorar e descobrir outros usuários na plataforma.

- **Postagens Próprias**: Os usuários podem criar e visualizar suas próprias postagens.

## Tecnologias Utilizadas

- [Next.js](https://nextjs.org) - Framework React para o frontend.
- [Golang](https://golang.org) - Linguagem de programação para o backend.
- [Fiber](https://gofiber.io) - Framework web para Golang.
- [MongoDB](https://www.mongodb.com) - Banco de dados NoSQL.
