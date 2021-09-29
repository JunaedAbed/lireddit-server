<!-- GETTING STARTED -->

## Getting Started

This is a Reddit clone.

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.

- Initialize
  ```sh
  npm init -y
  ```
- Install Typescript
  ```sh
  yarn add -D @types/node typescript
  ```
- Install ts-node
  ```sh
  yarn add -D ts-node
  ```
- Install tsconfig
  ```sh
  npx tsconfig.json
  ```
- nodemon
  ```sh
  yarn add -D nodemon
  ```
- watch mode
  ```sh
  yarn watch
  ```
- now run
  ```sh
  yarn dev
  ```
- now start postgresql
  ```sh
  brew services start postgresql
  ```
- now create migration
  ```sh
  npx mikro-orm migration:create
  ```
- install express
  ```sh
  yarn add -D @types/express
  ```
- install reflect-metadata
  ```sh
  yarn add reflect-metadata
  ```

### Installation

1. Setup MikroORM

```sh
 yarn add @mikro-orm/cli @mikro-orm/core @mikro-orm/migrations @mikro-orm/postgresql pg
```

2. Setup Graphql

```sh
 yarn add express apollo-server-express graphql type-graphql
```

<!-- 2. Enter your TOKEN in `.env`
   ```.env
   BOT_TOKEN = 'ENTER YOUR TOKEN'
   ``` -->
