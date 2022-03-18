# MERN app
Application built with React, Redux, Node.js, Express and MongoDB.
Registration and login form UI with RESTful API and authentication

## Backend:

RESTful API built from scratch with Node.js, Express, MongoDB and Mongoose

- CRUD operations
- Secure API by adding JWT authentication

### Install dependencies

#### Backend deps

```
npm init
npm i express dotenv mongoose colors
npm i -D nodemon
npm i express-async-handler
npm i bcryptjs
npm i jsonwebtoken

```

#### Run Server

```
npm run server / npm run dev
```

## Frontend:

React and Redux
-authentication using Redux Toolkit to manage global state

### Install dependencies

#### Frontend deps

```
npx create-react-app@latest frontend --template redux
npm i react-router-dom
npm i react-icons
npm i axios react-toastify
```

#### Run Server

```
npm run client/ npm run dev
```

#### To run both client & server the same time, install in the root

```
npm i -D concurrently
```
