# Gambling template casino

Casino with game of crash. In development used websockets (socket.io), node.js (adonis.js) and nuxt.js.

# Link storage (Linux):
sudo ln -s /absolute_path_to/casino/server/public/* /absolute_path_to/casino/static

## Client Setup

```bash
# install dependencies
$ npm install

# serve with hot reload at localhost:3000
$ npm run dev

# build for production and launch server
$ npm run build
$ npm run start

# generate static project
$ npm run generate
```

For detailed explanation on how things work, check out [Nuxt.js docs](https://nuxtjs.org).

## Server Setup

```bash
# goto server older
$ cd server

# install dependencies
$ npm install

# generate app key
$ adonis key:generate

# migrate database
$ adonis migration:run

# generate bots
$ adonis seed

# serve at localhost:3333
$ adonis serve
```

## Env (client) Setup
BASE_URL - url to server
CLIENT_URL - url to client

## Env (server) Setup
CLIENT_URL - url to client
