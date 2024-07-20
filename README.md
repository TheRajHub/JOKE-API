#🤖 Joke API

Welcome to the Joke API repository! This project is a simple yet powerful API that lets you manage a collection of jokes. Built with Express and body-parser, this API supports various operations like fetching random jokes, retrieving specific jokes, filtering jokes by type, and performing CRUD operations on the jokes database.
#Technologies Used
Backend: Node.js, Express
Middleware: body-parser

#npm install
#node index.js

API Endpoints
GET /random: Retrieve a random joke.
GET /jokes/:id: Fetch a specific joke by its ID.
GET /filter: Filter jokes by their type using a query parameter type.
POST /new: Add a new joke with jokeText and jokeType in the request body.
PUT /change/:id: Update a joke entirely by its ID.
PATCH /patch/:id: Update specific fields of a joke by its ID.
DELETE /delete/:id: Remove a specific joke by its ID.
DELETE /dall: Clear all jokes from the collection (requires key query parameter to match the master key).

