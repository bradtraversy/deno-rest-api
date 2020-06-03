# Deno REST API

> This is a REST API using Deno, Oak and PostgreSQL

Be sure to install [https://www.postgresql.org/](postgreSQL) and edit the "config.ts" file with your own credentials

* [Deno Crash Course Video](https://www.youtube.com/watch?v=NHHhiqwcfRM)
* [Deno & PostgreSQL Video](https://youtu.be/KuaI6mphFNc)

## Run

```
# This project uses Denon
deno start
```

## Routes

```
GET      /api/v1/products
GET      /api/v1/products/:id
POST     /api/v1/products
PUT      /api/v1/products/:id
DELETE   /api/v1/products/:id
```
