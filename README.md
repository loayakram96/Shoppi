# Shoppi
- Shopping list app built with the MERN stack along with Redux for state management, Reactstrap and react-transition-group.
- Authentication is implemented using JWT 

# How To Run:

- Add your MONGO_URI to the default.json file. Make sure you set an env var for that and the jwtSecret on deployment

```
# Install dependencies for server
  $ npm install

# Install dependencies for client
  $ npm run client-install

# Run the client & server with concurrently
  $ npm run dev

# Run the Express server only
  $ npm run server

# Run the React client only
  $ npm run client

# Server runs on http://localhost:5000 and client on http://localhost:3000
```

# Deployment
There is a Heroku post build script so that you do not have to compile your React frontend manually, it is done on the server. Simply push to Heroku and it will build and load the client index.html page

# App Info

The app is running and deployed on my Heroku: https://blooming-reaches-61307.herokuapp.com/
