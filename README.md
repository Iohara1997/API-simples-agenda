# API-Simples-Agenda

Uma API em Ruby on Rails com as principais rotas.

No diretório do arquivo, abrir terminal e digitar:

`rails s`, será executado na porta http://localhost:3000/

* [Get](localhost:3000/api/v1/contacts.json)

* [Get by ID](localhost:3000/api/v1/contacts/:id)

* [Post](localhost:3000/api/v1/contacts/:id)

* [Put](localhost:3000/api/v1/contacts/:id)

* [Delete](localhost:3000/api/v1/contacts/:id)

## Body

![Print](https://imgur.com/8ELshMi.png)

## Headers

No diretório do arquivo, abrir terminal e digitar:

`rails c`

O console do rails será iniciado. Crie então seu usuário:

`User.create(email: 'endereco@email.com', password: '123456'`

O comando gerará usuário e token de acesso que devem ser utilizados nos Headers das requisições.

![print](https://imgur.com/3YBgyrB.png)