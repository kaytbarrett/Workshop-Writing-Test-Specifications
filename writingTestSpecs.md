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


Functional Tests: 

1. A shopping cart checkout feature that allows a user to check out as a guest (without an account), or as a logged-in user. They should be allowed to do either, but should be asked if they want to create an account or log in if they check out as a guest.

- When a user clicks the "checkout" button, they shoud be shown a prompt asking if they would like to checkout as a guest or log into their account
- When a user clicks checkout a guest, they should be shown a prompt asking if they want to create an account or proceed to check out as a guest 
- When a user chooses to log into their account and click the "Log in" button, but used an incorrect password or username, they should be shown an error stating that the username or passoword was incorrect
- When a user clicks the "checkout" button, but their cart is empty, they should be shown an alert stating that their cart is empty and asks if they would like to continue shopping
