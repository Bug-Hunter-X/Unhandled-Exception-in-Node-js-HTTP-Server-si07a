# Unhandled Exception in Node.js HTTP Server

This repository demonstrates an example of an unhandled exception in a Node.js HTTP server and how to properly handle it.

## Bug

The `bug.js` file contains a simple HTTP server that throws an error if the request URL is '/error'. However, it does not handle this error properly, causing the server to crash.

## Solution

The `bugSolution.js` file demonstrates the proper way to handle exceptions in a Node.js HTTP server using a `try...catch` block.