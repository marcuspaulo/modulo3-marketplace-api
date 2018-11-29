# gonode-desafio-3

Desafio do Bootcamp GoNode - Rocketseat
Marketplace - API em NodeJS utilizando MongoDB

# Instalando as dependências do projeto

```sh
$ yarn install
```

# Rodando o projeto

```sh
$ yarn start
```

# Instalando o MongoDB através do Docker

```sh
$ docker run --name mongonode -p 27017:27017 -d -t mongo
```

# Iniciando o MongoDB através do Docker

```sh
$ docker start mongonode
```

# Acessando o MongoDB pelo navegador

[dill]: http://localhost:27017

# Instalando o Mongoose (ORM)

```sh
$ yarn add mongoose
```

# Instalando o BCrypt (Criptografia)

```sh
$ yarn add bcryptjs
```

# Autenticação BCryptJS

```sh
$ yarn add bcryptjs
```

# Instalando o Json Web Token (JWT)

```sh
$ yarn add jsonwebtoken
```

# Instalando o pacote Require DIR (Facilitar os imports)

```sh
$ yarn add require-dir
```

Basta chamar dessa forma (veja no routes.js)
Ou Seja, sem a necessidade de import individual dos Controllers

```
const controllers = require('./app/controllers/')

routes.post('/users', controllers.UserController.store)
```

# Instalando a paginação do Mongoose

```sh
$ yarn add mongoose-paginate
```

# Exemplos de Filtro na requisição:

{{ base_url  }}/ads?price_min=50

{{ base_url  }}/ads?price_max=10000

{{ base_url  }}/ads?title=Ferrari

{{ base_url  }}/ads?title=Ferrari&price_min=50

# Instalando a dependência para envio de e-mail

```sh
$ yarn add nodemailer
```

# Sugestão de servidores de e-mail:

[Desenvolvimento: https://mailtrap.io]

[Produção: Amazon SAAS, Send Grid, MailGun, Mandrill, SparkPost]

# Instalando a dependência para templates de e-mail

```sh
$ yarn add nodemailer-express-handlebars express-handlebars
```

# Instalando o REDIS

```sh
$ docker run --name noderedis -p 6379:6379 -d -t redis:alpine
```

# Iniciando o REDIS

```sh
$ docker start noderedis
```

# Instalando a dependência para trabalhar com fila (Queue)

```sh
$ yarn add kue
```

# Instalando a dependência para trabalhar com validação dos dados

```sh
$ yarn add joi
```

# Instalando a dependência para trabalhar com validação dos dados do Express

```sh
$ yarn add express-validation
```

# Instalando a dependência para formatar erros para Desenv

```sh
$ yarn add youch
```

# Instalando a dependência para formatar erros para trabalhar com async handle (function)

```sh
$ yarn add express-async-handler
```

# Instalando a dependência para monitorar erros na aplicação (em ambiente de produção)

[https://sentry.io] - Criar um projeto express e seguir as instruções

```sh
$ yarn add @sentry/node
```

# Instalando a dependência para o ambiente DotEnv

```sh
$ yarn add dotenv
```

# Template para o arquivo dotEnv (Raiz do projeto)

NODE_ENV=development
APP_SECRET=CHAVE_APLICACAO

DB_URL=mongodb://localhost:27017/gonode03

MAIL_HOST=smtp.mailtrap.io
MAIL_PORT=2525
MAIL_USER=USUARIO
MAIL_PASS=SENHA

REDIS_HOST=127.0.0.1
REDIS_PORT:6379

SENTRY_DSN=https://3acb3d3259b11b499b@sentry.io/1333060
