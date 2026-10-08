# MERN Blog Application

A full-stack blog learning project with a React client and Node.js/Express/MongoDB backend.

## Stack
- React and Material UI
- React Router and Axios
- Express and Mongoose
- JWT and bcrypt dependencies

## Structure
- `client/` — React application
- `server/` — Express API, routes, controllers, models, and database utilities

## Local development
Install dependencies in both directories:

```bash
cd server && npm install
cd ../client && npm install
```

Run the API and UI in separate terminals:

```bash
cd server
npm start
```

```bash
cd client
npm start
```

Configure the backend database, authentication secrets, and any upload storage before running. Avoid committing `.env` files or credentials.

## Status
Educational MERN application. Scripts and dependencies are from an older React/Node ecosystem; audit and upgrade before production deployment. This README does not imply production-ready security or automated test coverage.
