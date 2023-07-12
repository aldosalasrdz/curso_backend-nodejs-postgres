# Ecommerce API

This is a personal project developed during 1 month, it is a REST API created with the Express framework and PostgreSQL as a database that is executed with Docker Compose. Database queries are done through an ORM called Sequelize.

## Demo

🚧 Working on it

## Table of content

- [Pre-requisites](#pre-requisites)
- [Run locally](#run-locally)
- [Technologies used](#technologies-used)
- [API Reference](#api-reference)
- [Status](#status)
- [Author](#author)
- [License](#license)

## Pre-requisites

Before you start, make sure you have the following:

- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/)
- [Docker](https://www.docker.com/)
- [Docker Compose](https://github.com/docker/compose)
## Run Locally

Clone the project

```bash
git clone https://github.com/aldosalasrdz/nodejs-postgres.git --depth 1
```

Go to the project directory

```bash
cd nodejs-postgres
```

Install dependencies

```bash
npm install
```

Set environment variables

```bash
cp .env-example .env
```

Example:

```
PORT=3000
DB_USER='name'
DB_PASSWORD='secret_password'
DB_HOST='localhost'
DB_NAME='my_store'
DB_PORT='5432'
PG_EMAIL='example@mail.com'
PG_PASSWORD='admin_password'
PG_PORT=5050
PG_REFPORT=80
DATABASE_URL='postgres://YourUserName:YourPassword@YourHostname:5432/YourDatabaseName'
```

Create PostgreSQL and pgAdmin container

```bash
docker-compose up -d
```

Migrate the database

```bash
npm run migrations:run
```

Start the server

```bash
npm run dev
```

## API Reference

🚧 Working on it

## Technologies used

- Node
- Express
- Sequelize
- Docker Compose
- PostgreSQL

## Status

API version 1 completed. Working on GraphQL implementation.

## Author

- [@aldosalasrdz](https://www.github.com/aldosalasrdz)

## License

[MIT](https://choosealicense.com/licenses/mit/)
