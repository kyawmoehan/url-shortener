# URL Shortener with Node.js

- [Informaton](#information)
- [Installation And Starting](#starting)
- [Requirement](#requirement)
- [Packages](#packages)
- [About Project](#project)

## Infromation<a id="information"></a>

The project is simple URL shortener using Node.js, Express.js and MongoDB.The project use slug or short id for long URL that you provide.

## Installation And Starting<a id="starting"></a>

First go to server folder in project with cmd line tool.

```bash
$ cd server
```

Install dependencies:

```bash
$ npm install
```

Start Server:

```bash
$ npm start
```

Start Server with nodemon:

```bash
$ npm run dev
```

## Requirement

This project use .env file with dotenv package for MongoDB database URL.

You also need MongoDB in your machine to start local mongodb database.

Include these variables in .env file:

```bash
DATABASE_URL={mongodb_url}
```

## Packages

These are packages used in project:

- cors
- express
- helmet
- monk
- morgan
- nanoid
- yup

Dev Dependencies:

- dotenv
- nodemon
- eslint
- pretti

## About Project<a id="project"></a>

After starting server, the project will be running on http://localhost:3000. It will show main page with form to create url shortener.

It will ask slug and url.But if you don't provide slug, it will create slug for you. After it create scuccessfully it will show JSON data in the page.

To go to url http://localhost:3000/{slug}
