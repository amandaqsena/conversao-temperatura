# Projeto conversão de temperatura

[![CI](https://github.com/amandaqsena/conversao-temperatura/actions/workflows/main.yml/badge.svg)](https://github.com/amandaqsena/conversao-temperatura/actions/workflows/main.yml)

### Sobre o projeto
O projeto conversão de temperatura é um projeto desenvolvido em NodeJS. O projeto tem como objetivo ser um exemplo para a criação de ambiente com containers usando NodeJS.

### Observações do projeto
A aplicação é exposta usando a porta 8080

### Instalação e execução

Necessário Node.js

Dentro da pasta src, execute:

```
npm install
```

Depois disso, execute:

```
node server.js
```

## Usando Docker

docker build -t conversao .

docker container run -t conversao-temperatura

ou 

docker build -t amandaqsena/conversao-temperatura:v1
