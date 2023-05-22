# This is an [ExpressJS](https://expressjs.com/) project for Binar Fullstack Web Challenge

## Getting Started

First, install the node module depencies:

```bash
npm install
# or
yarn add
```
Then, run the application

```bash
npm start
# or
yarn start
```

Open [http://localhost:3030](http://localhost:3030) with your browser to see the result.

You can start editing the app by modifying `./app.js` in the root folder

## Endpoint

1. GET / to display home index page
   ```
   http://localhost:3030/

1. GET /user to display list of registered user

   ```
   http://localhost:3030/user

1. GET /login to display login page
   ```
   http://localhost:3030/login
   
1. POST /login to send user credention to login to the application
   ```
   http://localhost:3030/login
   
1. GET /unauthorized to redirect the unauthorized user 
   ```
   http://localhost:3030/unauthorized
   
1. GET /user/register to display registration page
   ```
   http://localhost:3030/user/register
   
1. POST /user/register to register user data
   ```
   http://localhost:3030/user/register
   
1. GET /play to display the game page
   ```
   http://localhost:3030/play
