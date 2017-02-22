# Hello_World-Node.js-
Hello_World with Node.js

#1 Hello Console
Editted the followin code gwith NotePad and saved as hello_world.js:

console.log("Hello world !");

Then open cmd and change the directory to the fold contains the hello_world.js file.
Type command   node hello_world.js
And then "Hello World !" will be showed in the console.





#2 Hello HTTP
A simple HTTP server that responds to every request with the plain text message "Hello World"
Editted the followin code gwith NotePad and saved as http.js:

// Load the http module to create an http server.
var http = require('http');

// Configure our HTTP server to respond with Hello World to all requests.
var server = http.createServer(function (request, response) {
  response.writeHead(200, {"Content-Type": "text/plain"});
  response.end("Hello World\n");
});

// Listen on port 8000, IP defaults to 127.0.0.1
server.listen(8000);

// Put a friendly message on the terminal
console.log("Server running at http://127.0.0.1:8000/");


Reference : Hello Node!, https://howtonode.org/hello-node
