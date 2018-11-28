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
