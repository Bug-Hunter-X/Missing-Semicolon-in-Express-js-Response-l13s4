# Missing Semicolon in Express.js Response

This repository demonstrates a common, yet easily overlooked, error in Express.js applications: a missing semicolon in the `res.send()` method.

## Bug
The `bug.js` file contains a simple Express.js server that responds with "Hello World". However, there's a missing semicolon at the end of `res.send('Hello World')`. This seemingly minor omission can lead to unexpected behavior, including syntax errors or unexpected responses.

## Solution
The `bugSolution.js` file corrects this error by adding the missing semicolon. This ensures that the code executes correctly and the server responds as intended.

## How to Reproduce
1. Clone this repository.
2. Navigate to the directory.
3. Run `node bug.js`.
4. Observe the unexpected behavior (e.g., the server might crash or respond incorrectly).
5. Run `node bugSolution.js`.
6. Observe the server responding correctly with "Hello World".

## Lesson Learned
Always pay close attention to syntax details. Missing semicolons, especially in JavaScript, can be a source of hard-to-debug issues.