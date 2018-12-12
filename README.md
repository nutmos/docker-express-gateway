# gateway

Generated by [Node Project Generator](https://github.com/robertoachar/generator-node).

[![License][license-badge]][license-url]

> A playground for Express Gateway and Docker.

# Development

* Cloning the repo

```bash
$ git clone https://github.com/robertoachar/docker-express-gateway.git
```

* Installing dependencies

```bash
$ cd heroes
$ npm install
$ cd ..

$ cd movies
$ npm install
$ cd ..

$ cd gateway
$ npm install
$ cd ..
```

* Running scripts

| Action                    | Usage          |
| ------------------------- | -------------- |
| Starting development mode | `npm start`    |
| Linting code              | `npm run lint` |

# Docker

* Building an image

```bash
$ docker-compose build
```

* Running a container

```bash
$ docker-compose up
```

* Stopping a container

```bash
$ docker-compose down
```

# Rest API

### Heroes Service

| Method | Endpoint        | Description                |
| ------ | --------------- | -------------------------- |
| GET    | /api/heroes     | Retrieves a list of heroes |
| POST   | /api/heroes     | Retrieves a specific hero  |
| GET    | /api/heroes/:id | Creates a new hero         |
| PUT    | /api/heroes/:id | Updates hero               |
| DELETE | /api/heroes/:id | Deletes hero               |

### Movies Service

| Method | Endpoint        | Description                |
| ------ | --------------- | -------------------------- |
| GET    | /api/movies     | Retrieves a list of movies |
| POST   | /api/movies     | Retrieves a specific movie |
| GET    | /api/movies/:id | Creates a new movie        |
| PUT    | /api/movies/:id | Updates movie              |
| DELETE | /api/movies/:id | Deletes movie              |

# Postman

* postman/docker-express-gateway.postman.json

# Author

[Roberto Achar](https://twitter.com/robertoachar)

# License

[MIT](https://github.com/robertoachar/docker-express-gateway/blob/master/LICENSE)

[license-badge]: https://img.shields.io/github/license/robertoachar/docker-express-gateway.svg
[license-url]: https://opensource.org/licenses/MIT
