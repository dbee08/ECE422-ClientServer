﻿# ECE422-ClientServer
Implement a client-server program in which the client will print the date and time given by the server. Two classes should be implemented: DateClient and DateServer.

The DateServer simply prints new Date().toString() whenever it accepts a connection and then closes the socket.

Write a client application that executes an infinite loop that

Prompts the user for a number.

Sends that value to the server.

Receives a number from the server.

Displays the new number.

Also write a server that executes an infinite loop whose body accepts a client connection, reads a number from the client, computes its square root, and writes the result to the client.
