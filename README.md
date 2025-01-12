# Uncaught TypeError: Cannot read properties of null (reading 'length')

This repository demonstrates a common JavaScript error: `Uncaught TypeError: Cannot read properties of null (reading 'length')`.  This error occurs when you try to access the `length` property of a variable that is currently `null` or `undefined`.

The `bug.js` file contains the erroneous code. The `bugSolution.js` file provides a corrected version that handles the `null` case gracefully.

## How to reproduce the bug

1. Clone the repository.
2. Open `bug.js` in your preferred code editor or IDE.
3. Run the code with a null value.
4. Observe the error message in your console.

## Solution

The solution involves adding a check to ensure that the variable is not null before accessing its `length` property.  The corrected code is in `bugSolution.js`.