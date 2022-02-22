<img align="center" src="https://i.imgur.com/XvHlmLg.jpg">

# Desafio: Introdução ao SOLID

<p align="center">
<img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/sabinorush/desafio-01-chapter-02">
<img src="https://img.shields.io/static/v1?label=Node.js&message=v14.16.1&color=brigthgreen&?style=flat&logo=Node.js">
<img src="https://img.shields.io/static/v1?label=yarn&message=v1.22.10&color=blue&?style=flat&logo=yarn">
</p>


<p align="center">
 <a href="#objetivo">Objetivo</a> •
 <a href="#rotas">Rotas</a> •
 <a href="#tecnologias">Tecnologias</a> •
 <a href="#como_executar">Como Executar</a> • 
</p>

<h2 id="objetivo">:dart: Objetivo</h2>

API de listagem e cadastro de usuários, desenvolvida durante o bootcam da [Rocketseat](https://rocketseat.com.br). A listagem de usuários é feita por um usuário admin e também é possível tornar um usuário comum em admin. Mais detalhes você pode conferir em rotas.

 Documentação da API com [Swagger](swagger.io/).

## Rotas

### POST `/users`

A rota deve receber `name`, e `email` dentro do corpo da requisição para que seja possível cadastrar um usuário.

### PATCH `/users/:user_id/admin`

A rota deve receber, nos parâmetros da rota, o `id` de um usuário e transformar esse usuário em admin.

### GET `/users/:user_id`

A rota deve receber, nos parâmetros da rota, o `id` de um usuário e devolver as informações do usuário encontrado pelo corpo da resposta.

### GET `/users`

A rota deve receber, pelo header da requisição, uma propriedade `user_id` contendo o `id` do usuário e retornar uma lista com todos os usuários cadastrados. O `id` deverá ser usado para validar se o usuário que está solicitando a listagem é um admin. O retorno da lista deve ser feito apenas se o usuário for admin.


<h2 id="tecnologias">:hammer_and_wrench: Tecnologias</h2>

![Jest](https://img.shields.io/badge/-jest-%23C21325?style=for-the-badge&logo=jest&logoColor=white)
![NodeJS](https://img.shields.io/badge/node.js-%2343853D.svg?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)

<h2 id="como_executar">:computer: Como Executar</h2>

```bash
# Clonando repositório
$ git clone https://github.com/sabinorush/desafio-01-chapter-02

# Entrando na pasta
$ cd desafio-01-chapter-02

# Instalando dependências
$ yarn

# Executando a aplicação em modo de desenvolvimento
$ yarn dev

# Inciando na porta:3333
acesse <http://localhost:3333>
```
### Docs

Para acessar a documentação, após fazer a instalação na sua máquina, acesse a rota [`/api-docs`](<http://localhost:3333/api-docs/>)

![](https://i.imgur.com/hEfKrJc.png)

Feito com :heart: <a href="https://github.com/sabinorush/">
 Gustavo Sabino</a> por 👋🏽 Entre em contato!

[![Linkedin Badge](https://img.shields.io/badge/-Gustavo_Sabino-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/gustavo-sabino/)](https://www.linkedin.com/in/gustavo-sabino/) 
[![Outlook Badge](https://img.shields.io/badge/Gustavo_Sabino-0078D4?style=flat-square&logo=microsoft-outlook&logoColor=white)](mailto:gu.sabino@hotmail.com)
