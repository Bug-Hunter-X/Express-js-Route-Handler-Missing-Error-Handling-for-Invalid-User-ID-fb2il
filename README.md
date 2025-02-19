# Express.js Route Handler Missing Error Handling for Invalid User ID

This repository demonstrates a common error in Express.js route handlers: the lack of error handling for invalid input.  Specifically, the `/users/:id` route attempts to parse the `id` parameter as an integer without checking for potential errors, leading to unexpected behavior if the ID is not a valid integer.

The `bug.js` file showcases the problematic code. The `bugSolution.js` file provides a corrected version that includes comprehensive error handling.