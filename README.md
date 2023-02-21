# FullStack social media app

This is a full stack social media app using React, Node.js, and MongoDB

# Important note

### This project does not have a mongoDB connection setup.
local development: create a .env
(make sure to name it .env) in the server folder, which exports your db.url connection.


# Install

Since this project will hold both the client application and the server application there will be node modules in two different places.
First run npm install from the root.

### Server-side usage(PORT3001)
```bash
$ cd server
$ npm i
$ npm run start
```

### Client-side usage(PORT: 3000)
```bash
$ cd client          // go to client folder
$ npm i              // npm install packages
$ npm run start      // run it locally
```

# Getting Started
#### Create a .env file in the server folder.
##### After you created .env file, you need to add your Mongo_URL,JWR_SECRET, and PORT.
Ex:
```bash
MONGO_URL='your-mongodb-url'
JWT_SECRET='something-hard-to-guess'
PORT=3001
```
