## Topics Covered

- Node.JS
- Express
- MongoDB (to store user information)
- JWT (JSON Web Tokens)
- Creating simple routes
- Creating Models / Schema
- Writing custom authentication middleware
- VS Code with Powershell as default terminal

## The flow of information is as follows:

> Client sends credentials to the server
> Server verifies the credentials, generates a JWT and sends it back as a response
> Subsequent requests from the client have a JWT in the request headers
> Server validates the token and if valid, provide the requested response.

## Instructions

- mkdir jwt-authentication
- cd jwt-authentication
- npm init --yes

# Start the server

`node index.js`
