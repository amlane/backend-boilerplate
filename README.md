# How to build a Node.js Server

A server using Node.js with Express, PostgreSQL, and Passport.js for Authentication.

## Setting up the Server

- [ ] Create a new Github repo, including a .gitignore for Node, a README and an MIT License (optional).
- [ ] Add a package.json file with the command `npm init -y`. Update the script to include:

```
"scripts": {
    "server": "nodemon",
    "start": "node index.js",
  }
```

- [ ] Install dependencies: `npm i express helmet cors knex sqlite3 dotenv pg`
- [ ] Install dev dependencies: `npm i nodemon -D`
- [ ] Create an index.js file for your port and a directory called "api" that will hold your server.js file. This is where we can organize our different server side routes.
