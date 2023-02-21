# FullStack social media app

This is a full stack social media app using React, Node.js, and MongoDB

# Important note

### This project does not have a mongoDB connection setup.
local development: create a .env
(make sure to name it .env) in the server folder, which exports your db.url connection.


# Install

Since this project will hold both the client application and the server application there will be node modules in two different places.
First run npm install from the root.

### Client-side usage(PORT: 3000)
```bash
$ cd client          // go to client folder
$ npm i              // npm install packages
$ npm run start      // run it locally
```
### Server-side usage(PORT6001)
```bash
// root level
$ cd server
$ npm i
$ npm run start
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
# File Structure

#### client - Holds the client application
##### public - Holds all of our static files
###### assets - Holds assets such as icons.
#### src
##### components - This folder holds all of the different components that will make up our views.
##### scenes - These represent a unique page on the website (Home, navbar, login, and profile). These are still normal react components
##### state - 
##### App.js - This is what renders all of our browser routes and different views
##### index.js - This is what renders the react app by rendering App.js, should not change
##### index.css - This make up our views
##### theme.js - This is contains the color of our views.
##### jsconfig.json - 

#### server - Holds the server application
##### controllers - 
##### data - 
##### middleware - Hold the token verification 
##### models - Set the models of data
##### public - Holds all of our static files such as images and icons
##### routes - 
##### index.js - 
##### .gitignore - 
##### README - This file :)
