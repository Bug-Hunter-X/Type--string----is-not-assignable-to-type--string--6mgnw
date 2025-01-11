# Type 'string[]' is not assignable to type 'string'

This repository demonstrates a common TypeScript error: attempting to pass an array of strings to a function expecting a single string.

The `bug.ts` file shows the erroneous code.  The `bugSolution.ts` file provides a corrected version.  The solution involves either modifying the function signature to accept an array or iterating through the array and calling the function for each element.

## How to Reproduce

1. Clone this repository.
2. Navigate to the directory in your terminal.
3. Run `tsc bug.ts` (you'll need TypeScript installed).
4. Observe the compilation error.