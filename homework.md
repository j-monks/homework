Questions
1. What is responsible for defining the routes of the games resource?
A. gamesRouter & create_router.js

2. What do you notice about the folder structure? Whats the client responsible for? Whats the server responsible for?
A.  client is responsible for the front end and the server is responsible for the backend

3. What are the the responsibilities of server.js?
A. allows cross communcation via cors & sets up a server listening on port 3000, also directs users data to create_router file.

4. What are the responsibilities of the gamesRouter?
A. is responsible for taking whatever data that comes in and 'interpolates' it to the relevant routes, so to make the router dynamic.

5. What process does the the client (front-end) use to communicate with the server?
A. it's communicating with it in the services folder/gamesservice.js not really sure but it seems like gameservice is then being imported into components and then appended onto the start of functions and then thats making a fetch to the server?

6. What optional second argument does the fetch method take? And what is it used for in this application? Hint: See Using Fetch on the MDN docs
A. an init object, that lets you control a few different settings e.g the request type, body & headers information. Here we are creating a game POST & DELETING a game 

7. Which of the games API routes does the front-end application consume (i.e. make requests to)?
A. 

8. What are we using the MongoDB Driver for?