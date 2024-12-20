# ActionScript IndexOutOfBoundsException Bug

This repository demonstrates a common ActionScript error: attempting to access an array element using an index that is out of bounds.  This often happens when you try to access the element at index equal to the length of the array, which is one element past the last valid index.

The `bug.as` file contains code that reproduces the error. The `bugSolution.as` file demonstrates a corrected version.

## How to reproduce

1.  Copy the code from `bug.as` into an ActionScript environment (such as FlashDevelop or Animate).
2.  Run the code. You should see an error message similar to "Error: IndexOutOfBounds".

## Solution

The solution lies in ensuring that the index used to access array elements is always within the valid range (0 to length - 1). See `bugSolution.as` for the corrected code.