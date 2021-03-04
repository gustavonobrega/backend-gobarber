<h1 align="center">
  <br>
    <img src="logo.svg" alt="GoBarber">
  <br>
  <br>
    GoBarber API
</h1>

<p align="center">An api for barber appointment and scheduling</p>

<p align="center">
  <a href="https://opensource.org/licenses/MIT">
    <img src="https://img.shields.io/badge/license-MIT-orange" alt="License MIT">
  </a>
    <a href="https://github.com/gustavonobrega">
    <img src="https://img.shields.io/badge/author-gustavonobrega-orange" alt="Author">
  </a>
</p>

<hr />

## 🚀 Technologies

A Node.js API built with Express and all the latest tools and best practices in development!

- [Node.js](https://nodejs.org/en/)
- [Docker](https://www.docker.com/)
- [TypeScript](https://www.typescriptlang.org/)
- [Express](https://expressjs.com/pt-br/)
- [Multer](https://github.com/expressjs/multer)
- [TypeORM](https://typeorm.io/#/)
- [JWT-token](https://jwt.io/)
- [uuid v4](https://github.com/thenativeweb/uuidv4/)
- [PostgreSQL](https://www.postgresql.org/)
- [MongoDB](https://www.mongodb.com/)
- [Redis](https://redis.io/)
- [Nodemailer](https://nodemailer.com/)
- [Handlebars](https://handlebarsjs.com/)
- [Date-fns](https://date-fns.org/)
- [Jest](https://jestjs.io/)
- [Eslint](https://eslint.org/)
- [Prettier](https://prettier.io/)
- [EditorConfig](https://editorconfig.org/)

## 🗒 Prerequisites

To run this server you will need three containers running on your machine.

To do so, you will need to run the following commands:

- `docker run --name redisbarber -p 6379:6379 -d -t redis:alpine`;
- `docker run --name mongodb -p 27017:27017 -d -t mongo`;
- `docker run --name database -e POSTGRES_PASSWORD=docker -p 5433:5432 -d postgres`;

_Remember: If you restart your machine, you will need to start again the server with `docker start <container_id>`.

## 💻  Getting started

_Consider checking out the FrontEnd [repository](https://github.com/gustavonobrega/gobarber-web)!_

1. Clone this repo using `https://github.com/gustavonobrega/backend-gobarber`
2. Move to the appropriate directory: `cd backend-gobarber`.<br />
3. Run `yarn` to install dependencies and `yarn typeorm migration:run` to execute typeorm migrations.<br />
4. Copy the `.env.example` file and rename it to `.env`.<br/>
5. Add all the values for the environment variables.<br/>
6. Run `yarn dev:server` to run the servers.

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Made with ♥ by Gustavo Nobrega
