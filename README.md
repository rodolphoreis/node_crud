# Node.js CRUD Application with Express, TypeORM, and PostgreSQL

Este é um exemplo de uma aplicação CRUD (Create, Read, Update, Delete) em Node.js integrando um banco de dados PostgreSQL usando Express e TypeORM.

## Pré-requisitos

Antes de começar, certifique-se de ter as seguintes ferramentas instaladas em sua máquina:

- Node.js
- PostgreSQL

## Configuração do Banco de Dados

1. Certifique-se de ter o PostgreSQL instalado e em execução em sua máquina.
2. Crie um banco de dados no PostgreSQL para a aplicação.
3. Configure as credenciais do banco de dados no arquivo `ormconfig.json`.

## Instalação

1. Clone este repositório em sua máquina local.
2. Navegue até o diretório do projeto.
3. Execute o comando `npm install` para instalar as dependências.

## Configuração do TypeORM

1. Após instalar as dependências, execute o comando `typeorm init --name MyProject --database postgres` para inicializar o TypeORM no projeto.
2. Configure as conexões do banco de dados no arquivo `ormconfig.json`.

## Executando a Aplicação

1. Após a configuração do banco de dados e do TypeORM, execute o comando `npm start` para iniciar o servidor.
2. A aplicação estará disponível em `http://localhost:3000` por padrão.

## Endpoints da API

A seguir estão os endpoints da API disponíveis:

- `GET /api/users`: Retorna todos os usuários.
- `GET /api/users/:id`: Retorna um usuário específico pelo ID.
- `POST /api/users`: Cria um novo usuário.
- `PUT /api/users/:id`: Atualiza um usuário existente pelo ID.
- `DELETE /api/users/:id`: Exclui um usuário pelo ID.

## Contribuição

Sinta-se à vontade para contribuir com melhorias ou correções para este projeto! Basta seguir estas etapas:

1. Faça um fork deste repositório.
2. Crie uma nova branch para sua funcionalidade (`git checkout -b feature/nova-funcionalidade`).
3. Faça commit de suas alterações (`git commit -am 'Adicionando nova funcionalidade'`).
4. Faça push para a branch (`git push origin feature/nova-funcionalidade`).
5. Envie um pull request.


