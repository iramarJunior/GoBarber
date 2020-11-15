# GoBarber
Aplicação desenvolvida dentro do Bootcamp GoStack 13 da Rocketseat.


## How to start Service

- Start Postgres from Docker;
    ```
    $ docker run --name postgres -p 5432:5432  -e POSTGRES_PASSWORD=docker -d postgres
    ```
- Create a Database;
- Start aplication;
    ```
    $ cd /service
    $ yarn
    $ yarn dev:server
    ```

## How to start Web

```
$ cd /web
$ yarn
$ yarn start
```