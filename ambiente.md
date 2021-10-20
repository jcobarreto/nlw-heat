yarn init -y
yarn add express
yarn add -D @types/express typescript ts-node-dev
yarn tsc --init
## Retirar os comentários do arquivo package.json

## Add o trecho abaixo ao package.json
  "scripts": {
    "dev": "ts-node-dev src/app.ts"
  },

yarn dev
yarn add prisma -D
yarn init prisma 
yarn add dotenv

## Acessar o Github e criar um OAuth app
https://github.com/settings/developers

## Adicionar ao arquivo .env as entradas abaixo com as informações obtidas no passo anterior
GITHUB_CLIENT_SECRET=
GITHUB_CLIENT_ID=

yarn add axios
yarn add @types/axios -D
yarn add jsonwebtoken
yarn add @types/jsonwebtoken -D
yarn add socket.io
yarn add @types/socket.io -D
yarn add cors
yarn add @types/cors -D
