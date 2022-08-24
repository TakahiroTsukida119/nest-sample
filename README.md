## Description
[Nest](https://github.com/nestjs/nest) framework TypeScript starter repository.

## Spec
| name | version |
|------|---------|
| Nest | 9.0.0   |
| Node | 14.17.0 |

## Setup

```bash
$ git clone https://github.com/TakahiroTsukida119/nest-sample.git
$ cd nest-sample
$ make up
```

## Docker Container
```shell
$ make ps
CONTAINER ID   IMAGE             COMMAND                  CREATED         STATUS         PORTS                    NAMES
72849eefb5d8   node-server_app   "docker-entrypoint.s…"   9 seconds ago   Up 8 seconds   0.0.0.0:3000->3000/tcp   nest-app
```


## Installation

```bash
$ yarn install
```

## Running the app

```bash
# development
$ yarn run start

# watch mode
$ yarn run start:dev

# production mode
$ yarn run start:prod
```

## Test

```bash
# unit tests
$ yarn run test

# e2e tests
$ yarn run test:e2e

# test coverage
$ yarn run test:cov
```

## Support

Nest is an MIT-licensed open source project. It can grow thanks to the sponsors and support by the amazing backers. If you'd like to join them, please [read more here](https://docs.nestjs.com/support).

## Stay in touch

- Author - [Kamil Myśliwiec](https://kamilmysliwiec.com)
- Website - [https://nestjs.com](https://nestjs.com/)
- Twitter - [@nestframework](https://twitter.com/nestframework)

## License

Nest is [MIT licensed](LICENSE).
