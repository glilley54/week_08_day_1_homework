# Games Hub

Games Hub is a full stack JavaScript application with an Express server and MongoDB database.

## Getting Started

These instructions will get the project up and running on your local machine for development purposes.

### Installing

Install dependencies in both the client and the server folders:

```
cd client
npm install

cd server
npm install
```

Seed the database.  Within the server folder:

```
npm run seeds
```

Run express (leave running in a terminal window).  Within the server folder:

```
npm run server:dev
```

Run React environment (leave running in a terminal window).  Within client folder:

```
npm start
```

### Using

The application is running on port 3000 so visit http://localhost:3000/.


Questions
What is responsible for defining the routes of the games resource?

 <!-- express framework in server.js  -->

What do you notice about the folder structure? Whats the client 
responsible for? Whats the server responsible for?

<!-- Client folder containers the games container and all of the game components which hold the props passed down from the container.
This is all the client side(frontend) files.Server is the middle layer between front end and the backend which passes data back and forth based on requests made from the front end. -->



What are the the responsibilities of server.js?

<!-- Server.js is the file that acts as go between for datbase(mongo) and front end using express.  -->

What are the responsibilities of the gamesRouter?

<!-- to keep restful routes to the browser to stop repitition and keep the code dry -->

What process does the the client (front-end) use to communicate with the server?

<!-- Http requests made from browser -->

What optional second argument does the fetch method take? And what is it used for in this application? Hint: See Using Fetch on the MDN docs


<!-- an init object that allows you to control a number of different settings: -->

Which of the games API routes does the front-end application consume (i.e. make requests to)?

<!-- get route -->

What are we using the MongoDB Driver for?


<!-- To allow our js.node applications connect to MongoDB and work with data  -->
