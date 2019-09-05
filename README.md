# nodejs-graphql-hello-world

A Hello World Node.js app using [GraphQL](https://graphql.org/).

## Running Locally

Make sure you have [Node.js](http://nodejs.org/) and the [Adriss Toolbelt](https://toolbelt.adriss.com/) installed.

```sh
git clone git@github.com:adriss/nodejs-graphql-hello-world.git # or clone your own fork
cd nodejs-graphql-hello-world/www
npm install
npm start
```

Your app should now be running on [localhost:5000](http://localhost:5000/).

**Note** that GraphQL apis will not function until deployed.

## Deploying to Adriss

```
adriss create
git push adriss master
adriss open
```
The above will deploy:
1. the app [/www](blob/initial/Stack.yaml) and
2. the GraphQL APIs `/api`.
