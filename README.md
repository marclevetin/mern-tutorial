# Overview
This project was my first attempt in the MERN stack (MongoDB, Express, React, Node).  I followed a tutorial found here: https://medium.com/@bryantheastronaut/react-getting-started-the-mern-stack-tutorial-feat-es6-de1a2886be50.  Because the tutorial was close to a year old, there were many changes to tools used, especially with Create-React-App and Mongoose.

## Things I learned/used for the first time.
1. Postman
2. Mongo
3. Express
4. Node
5. Putting CSS in a JS wrapper
6. Assorted tools:
  * Axios: let us use HTTP methods to communicate with our database.
  * Express: provide a framework to set up our Node.js server.
  * Body Parser: parse the incoming requests bodies for the info we are sending (gives us access to `req.body` which we will be using soon).
  * Foreman: allows us to boot up our API and webpack-dev-server simultaneously.
  * Nodemon: watches our server.js file for changes, then restarts it.
  * Marked: to convert markdown syntax to html. I used this in place of Remarkable (which the FB tutorial uses)
  * Mongoose: abstracts away the MongoDB boilerplate for a simple Schema solution.

## Getting started
_Requires an account at MLab.  See the tutorial for details_
1. Clone the tutorial
2. Open a terminal
3. Create a `.env` file with two key=value pairs: `DB_USER`, and `DB_PASS`.  These keys correspond to your MLab credentials.
4. `npm run start-dev`.  This will start both the webserver on port 3000 and API on port 3001.  (Instructions for this are held in the procfile)
