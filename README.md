# TypeORM

## Setup

```sh
# criação do container
docker run --name gostack_postgres -e POSTGRES_PASSWORD=docker -p 5432:5432 -d postgres
# caso ele já exista:
# docker start gostack_postgres

# criar o banco gostack_desafio09
# criar tabelas com typeorm
#yarn typeorm migration:run

yarn

# criação de tabelas
yarn typeorm migration:run
```

## Test

```sh
# criar o banco gostack_desafio09_tests

yarn test
```
