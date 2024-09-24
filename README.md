# Expense Tracker App with GraphQL

Welcome to the MERN GraphQL Expense Tracker App! This project is designed to help you manage your expenses efficiently using a modern tech stack and GraphQL.

https://raw.githubusercontent.com/iam-mayur/pp-expense-tracker-gql/master/assets/expense-tracker.mp4

## Features:

- 🌟 Tech stack: MERN (MongoDB, Express.js, React.js, Node.js) + Apollo GraphQL
- 📝 Learn type definitions and resolvers for defining GraphQL schema and data fetching logic
- 🔄 Mutations for modifying data in the GraphQL API and establishing graph relations
- 🎃 Authentication with Passport.js and MongoDB session store
- 🚀 Global state management with Apollo Client
- 🐞 Error handling both on the server and on the client
- ⭐ Deployment made easy with a platform called Render
- 👾 Cron jobs for scheduled tasks and automation
- ⏳ And much more!

<div align="center"><img height="350" width="700" alt="" src="https://raw.githubusercontent.com/iam-mayur/pp-expense-tracker-gql/master/assets/expense-tracker-ui.png" /></div>

## Setup .env file

```js
MONGO_URI=...
SESSION_SECRET=...
PORT=...
```

## Install dependencies

```sh
cd frontend && npm i
cd .. && npm i
```

## Build the app

```shell
npm run build
```

## Start the app

```shell
npm start
```

Adjust _npm start_ script according to runtine environment as shown below

- Unix : "NODE_ENV=production node backend/index.js"
- Windows : "SET NODE_ENV=production & node backend/index.js"
