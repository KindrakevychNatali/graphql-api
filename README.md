
---

# GraphQL API

A simple GraphQL API built using Apollo Server and GraphQL.

## Project Overview

This project is a basic GraphQL API developed with Node.js, Apollo Server, and GraphQL. The main goal is to provide a starting point for building GraphQL APIs.

### Features

- **Apollo Server**: A fully-featured GraphQL server with a simple setup.
- **GraphQL**: A query language for APIs and a runtime for executing those queries.
- **Nodemon**: Automatic server restarts during development.

## Prerequisites

Before you start, make sure you have the following installed on your system:

- [Node.js](https://nodejs.org/) (v14 or later)
- [npm](https://www.npmjs.com/) (v6 or later) or [Yarn](https://yarnpkg.com/)

## Installation

To get started, clone the repository and install the dependencies:

```bash
git clone https://github.com/KindrakevychNatali/graphql-api.git
cd graphql-api
npm install
```

## Running the API

To start the GraphQL API in development mode, use the following command:

```bash
npm start
```

This will run the server using `nodemon`, which automatically restarts the server when you make changes to the source files.

### Accessing the API

Once the server is running, you can access the GraphQL Playground at:

```
http://localhost:4000/
```

The GraphQL Playground allows you to interact with your API, run queries, and test mutations.

## Project Structure

- **`index.mjs`**: The entry point for the application where the Apollo Server is configured and started.
- **`graphql/`**: This directory (if exists) should contain your schema, resolvers, and other related files.

## Dependencies

- **apollo-server**: The core package for setting up an Apollo GraphQL server.
- **colors**: A package to add colors to your console logs (optional).
- **graphql**: The reference implementation of the GraphQL query language for JavaScript.
- **nodemon**: A tool that helps develop Node.js applications by automatically restarting the server when file changes are detected.

## Author

**Kindrakevych Nataliia**

## License

This project is licensed under the ISC License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [Apollo GraphQL](https://www.apollographql.com/) for the server implementation.
- [GraphQL](https://graphql.org/) for the query language.

---
