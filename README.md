# Conceitos-nodejs
## Primeiro desafio de nodejs do bootcamp GoStack.
Nesse desafio foi criado uma aplicação com o armazenamento em memória.
Essa será uma aplicação para armazenar repositórios do seu portfólio, que irá permitir a criação, listagem, atualização e remoção dos repositórios, e além disso permitir que os repositórios possam receber "likes".

## Como usar?
- Assim que abrir o projeto no editor de codigo execulte um `yarn` para instalar as dependência do projeto.
- Após isso, pode rodar um `yarn dev` para rodar a aplicação que ficará disponível no endereço `http://localhost:3333`.
- Está disponível também os teste, para execultar, basta rodar `yarn test` e `jest` e `supertest` ira rodar a rotina de teste.

## Rotas da aplicação

- POST `/repositories:` A rota deve receber title, url e techs dentro do corpo da requisição, para criar um repositório;

- GET `/repositories:` Rota que lista todos os repositórios;

- PUT `/repositories/:id:` A rota atualiza um repositório desejado;

- DELETE `/repositories/:id:` A rota deleta um repositório desejado;

- POST `/repositories/:id/like:` A rota atualiza os likes do repositório desejado;