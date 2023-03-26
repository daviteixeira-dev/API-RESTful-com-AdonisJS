<p align="center">
  <a href="https://adonisjs.com/">
    <img src="https://avatars.githubusercontent.com/u/13810373?s=280&v=4" alt="Logo" width="" height="100" />
  </a>
</p>

<h1 align="center"> API RESTful com AdonisJS </h1>

<p align="center">
  <a href="#Introdução"> 🧩 Introdução </a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#Resultados"> 🚀 Resultados</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#Dependências"> 🧪 Dependências</a>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</p>

<a id="Introdução"></a>
## 🧩 Introdução

### É um framework que está sendo muito utilizado para construir APIs como também softwares monolitos, que tem o front-end junto ao backend, 
deixando assim muitas funcionalidades prontas, escrevendo menos códigos e tendo resultados mais rápidos para o desenvolvedor.

<ul>
  <li>Um <b>framework Node.js</b>, para desenvolver aplicações web;</li>
  <li>Facilita muito a programação de apps, possui uma estrutura similar ao <b>Laravel</b>;</li>
  <li>Utilizar arquitetura <b>MVC</b>;</li>
  <li>Possui vários recursos, como: <b>CLI</b>, <b>File upload</b> simples, <b>validações</b> e etc;</li>
  <li>Há também outros pacotes externos para completar o ecossistema, como <b>ORM</b>, <b>Autenticação</b>, <b>Autorização</b>.</li>
</ul>

<a id="Resultados"></a>
## 🚀 Resultados 

### O resultado desse projeto é a criação de uma <b>API RESTful</b> onde temos um <b>CRUD</b> e relacionamento entre entidades, aprendendo a como utilizar o framework. Os 
testes foram feitos via <b>Postman</b>, para garantir o correto funcionamento da API.

## 💻 Back-end

### Moments

### 🎯 Pegar um momento atravez do ID

### ```GET``` 
```URL
 http://localhost:3333/api/moments/1
```

### 🎯 Pegar todos os momentos

### ```GET ALL``` 
```URL
 http://localhost:3333/api/moments
```

### 🎯 Registrar um momento no banco de dados
  
### ```POST``` 
```URL
http://localhost:3333/api/moments
```
  
```Body
from-data

key (text): title - value: Algum valor
key (text): description - value: Alguma descrição
key (file): image - value: Alguma imagem do seu pc
```

### 🎯 Atualizar um momento no banco de dados
  
### ```PATCH``` 
```URL
http://localhost:3333/api/moments/1
```
  
```Body
from-data

key (text): title - value: Atualizando Momento
key (text): description - value: Meu momento atualizado
key (file): image - value: Alguma imagem do seu pc
```
### Comments

### 🎯 Add um comentário

###```POST```
```URL
http://localhost:3333/api/moments/1/comments
```

```JSON

{
  "username": "Seu Nome",
  "text": "Algum outro comentário"
}
```

<a id="Dependências"></a>
## 🧪 Dependências
> Requisitos para rotar o codigo...

## `📖 Scripts` 

```JSON
"scripts": {
  "dev": "node ace serve --watch",
  "build": "node ace build --production",
  "start": "node server.js",
  "test": "node ace test",
  "lint": "eslint . --ext=.ts",
  "format": "prettier --write ."
}

```
## `📖 Dependencies` 

```JSON
"dependencies": {
  "@adonisjs/core": "^5.8.0",
  "@adonisjs/lucid": "^18.3.0",
  "@adonisjs/repl": "^3.1.0",
  "luxon": "^3.3.0",
  "proxy-addr": "^2.0.7",
  "reflect-metadata": "^0.1.13",
  "source-map-support": "^0.5.21",
  "sqlite3": "^5.1.6",
  "uuid": "^9.0.0"
}

```
<br /> 

## `📖 devDependencies` 

```JSON
"devDependencies": {
  "@adonisjs/assembler": "^5.9.5",
  "@japa/preset-adonis": "^1.2.0",
  "@japa/runner": "^2.5.1",
  "@types/proxy-addr": "^2.0.0",
  "@types/source-map-support": "^0.5.6",
  "adonis-preset-ts": "^2.1.0",
  "eslint": "^8.36.0",
  "eslint-config-prettier": "^8.8.0",
  "eslint-plugin-adonis": "^2.1.1",
  "eslint-plugin-prettier": "^4.2.1",
  "pino-pretty": "^10.0.0",
  "prettier": "^2.8.6",
  "typescript": "~4.6",
  "youch": "^3.2.3",
  "youch-terminal": "^2.2.0"
}

```
