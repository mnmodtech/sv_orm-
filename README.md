# SV ORM

# ORM Full-Stack Serverless Starter

## Authors

- [@nkendrick101](https://www.github.com/nkendrick101)

## Features

- Typescript
- PSQL
- Serverless
- Tailwind

## Tech Stack

**Client:** Next.js, TailwindCSS

**Server:** Node, Postgres

## API Reference

#### Get all items

```http
  GET /api/users
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

#### Get item

```http
  GET /api/users/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |

## Roadmap

## Installation

clone

```bash
  npm install my-project
  cd my-project
```

```
# Create .env variables 
```

```
DB_HOST=myhost_local
DB_USER=myuser_local
DB_PASS=mypassword_local
DB_NAME=mydatabase_local
DB_URL=mydburlstring_local
JWT_KEY="secretOrKeyJWTRandom"
```

# Migrations & Seed commands

**Sequelize database migration and seed command**

`sequelize db:migrate` to execute database migrations.

`sequelize db:seed:all` to execute all table seeders.

**Sequelize undo database migration and seed command**

`sequelize db:migrate:undo:all` to undo database migrations.

`sequelize db:seed:undo:all` to undo seeders.




**Deployment on Vercel**

Install Vercel Cli `npm i -g vercel` or `yarn add global vercel` and see this [link](https://vercel.com/docs/cli#getting-started) for available commands. This will enables you to [instant cloud deployment](https://vercel.com/now) and [local development](https://vercel.com/blog/now-dev). Follow the instruction and press enter for your setup choice. Just type `vercel --prod` to deploy or update the changes in your root terminal.
