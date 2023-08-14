Unit Tests:

1. A function called "multiplication" that returns the product of the two input number:

- expect multiplication(a,b) to be a number
- expect multiplication(2,3) to be 6
- expect multiplication("a",3) to be an error
- expect multiplication(2,"b") to be an error


2. A function called "concatOdds" takes two arrays of integers as arguments. It should return a single array that only contains the odd numbers, in ascending order, from both of the arrays.

- expect concatOdd([3, 2, 1], [9, 1, 1, 1, 4, 15, -1]) to result in [-1, 1, 3, 9, 15]
- expect concatOdd(["a", "b", "c"], ["d", "e", "f"]) to be an error
- expect concatOdd(["a", 3, 2, "c"], ["d", 5, 6, "f"]) to be an error
- expect concatOdd([3, 3, 3, 3]), [5, 5, 5, 5,] to result in [3, 5]