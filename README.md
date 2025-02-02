# Unhandled Promise Rejection in Express.js Async Route Handler

This repository demonstrates a common error in Express.js applications: unhandled promise rejections in asynchronous route handlers.  The `bug.js` file shows an example of an Express.js application where an asynchronous operation within a route handler lacks proper error handling.  This can lead to unexpected application crashes or silent failures, making debugging difficult. 

The `bugSolution.js` file provides a corrected version with comprehensive error handling, showing best practices for handling errors in asynchronous operations within an Express.js application.  The solution showcases how to use a central error handler to gracefully manage unexpected errors, preventing crashes and providing informative error messages.

## How to Reproduce the Bug

1. Clone the repository.
2. Navigate to the repository directory.
3. Run `node bug.js`.
4. Observe the occasional crashes or missing error messages in the console.

## Solution

Refer to the `bugSolution.js` file for the corrected code and detailed explanation of the improvements.