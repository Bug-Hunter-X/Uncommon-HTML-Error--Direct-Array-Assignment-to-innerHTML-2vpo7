# Uncommon HTML Error: Direct Array Assignment to innerHTML

This repository demonstrates an uncommon error in HTML related to the `innerHTML` property.  Attempting to directly assign a JavaScript array to `innerHTML` will result in an unexpected outcome.

The `bug.html` file shows the erroneous code, while `bugSolution.html` presents the correct approach.

The error arises from the misuse of `innerHTML` which expects a string value, not an array. The solution involves converting the array to a string before assignment.
