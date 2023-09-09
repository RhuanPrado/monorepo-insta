# Projeto de Rede Social Simples com Next.js e Golang

Este é um projeto de uma aplicação de rede social simples desenvolvida com Next.js para o frontend e Golang (utilizando o framework Fiber) para o backend. O banco de dados utilizado é o MongoDB. O propósito deste projeto é demonstrar minhas habilidades de desenvolvimento web.

## Como Rodar o Projeto

### Pré-requisitos

Antes de começar, certifique-se de ter o Docker e o Docker Compose instalados em sua máquina.

### Passo 1: Clone o Repositório

Clone este repositório para a sua máquina usando o seguinte comando:

```bash
git clone https://github.com/RhuanPrado/monorepo-insta
```

### Passo 2: Navegue até o Diretório do Projeto

Navegue até o diretório do projeto recém-clonado:

```bash
cd monorepo-insta
```

### Passo 3: Configure as Variáveis de Ambiente

Crie um arquivo `.env` no diretório raiz do projeto e configure as variáveis de ambiente necessárias. Você pode usar o arquivo `.env.example` como referência.
Para go-api-insta preencha:

#### .env

```env
PORT=3003
JWT_KEY=g04p11574
MONGODB_URI=mongodb://insta:insta@mongodb-insta:27017
DATABASE_NAME=insta
```

Crie um arquivo `.env.local` no diretório raiz do projeto e configure as variáveis de ambiente necessárias. Você pode usar o arquivo `.env.example` como referência.
Para spa-insta preencha:

#### .env.local

```env
NEXT_PUBLIC_API_URL=http://localhost:3003
```

### Passo 4: Navegue até o Diretório do Projeto

Navegue até o diretório do projeto `/etc`:

```bash
cd etc/
```

### Passo 5: Inicie o Projeto com Docker Compose

Use o Docker Compose para construir e iniciar os contêineres do frontend, backend e banco de dados:

```bash
docker-compose up --build
```

Isso irá construir as imagens Docker e iniciar os serviços. Aguarde até que todos os serviços estejam em execução.

### Passo 6: Acesse a Aplicação

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

## Contribuição

Este projeto foi criado para fins de demonstração de habilidades. Se você deseja contribuir, sinta-se à vontade para abrir um problema ou enviar uma solicitação pull.

## Licença

Este projeto é licenciado sob a licença MIT. Consulte o arquivo [LICENSE](LICENSE) para obter mais detalhes.
