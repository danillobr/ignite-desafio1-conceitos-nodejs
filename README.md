<p align="center">
  <img src=".github/capa-ignite-nodejs.png" alt="Ignite Node.js">
</p>

<br>

<h1 align="center">
  Desafio 1: conceitos do NodeJS
</h1>

<br>

<p align="center">
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js">
  <img src="https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E" alt="JavaScript">
  <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express.js">
</p>

## :computer: Descrição:
Esta é uma API para gerenciar tarefas (em inglês todos), em que é permitida a criação de um usuário com `name` e `username` bem como fazer o CRUD (Create, Read, Update and Delete ) de todos.

## :hammer_and_wrench: Funcionalidades:
- [x] Criar uma nova todo.
- [x] Listar todas as todos.
- [x] Alterar o `title` e `deadline` de um todo existente.
- [ ] Marcar uma todo como `done`.
- [ ] Excluir uma todo.

## :link: Rotas:
- POST `/users`: cria um novo usuário.
- GET `/todos`: retorna uma lista com as todos de um usuário.
- POST `/todos`: cria uma nova todo.
- PUT `/todos/:id`: atualiza o `title` e o `dealine` de uma todo.
- PATCH `/todos/:id/done`: finaliza o `done` de uma todo.
- DELETE `/todos/:id`: remove uma todo.

## :memo: Execução da API:
- Instalação das dependências:
  > yarn

- Execução da API:
  > yarn dev

- Execução dos testes:
  > yarn test
