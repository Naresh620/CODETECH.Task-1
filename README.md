Name: Naeshkrishna M
ID: CT4PP5061
Domain: Python Programming
Dates: July 15th, 2024 - August 15th, 2024
Overview:
Functions for Operations: The script defines basic arithmetic operations (add, sub, mul, div) as separate functions.
Dictionary for Operations: operation_dict maps arithmetic symbols (+, -, *, /) to their corresponding functions.
User Input Handling:
The calculator() function prompts the user for numbers and an operation choice.
It performs the chosen arithmetic operation on the numbers.
It allows the user to continue with the result, start a new calculation, or exit.
Recursion for New Calculations:
If the user chooses to start a new calculation ('n'), it clears the screen (using os.system('cls')) and recalls calculator() recursively.
This allows for nested calculations until the user chooses to exit.
Technologies Used:
Python Basics: Functions, loops, conditional statements (if, elif, else).
Dictionary: Used to store functions for dynamic operation selection based on user input.
Recursion: Recursively calls calculator() to handle nested calculations or restarts.
OS Module: Utilizes os.system('cls') to clear the screen, enhancing user interface clarity.
Functionality:
The calculator supports basic arithmetic operations.
Handles user input for numbers and operation choices.
Provides options to continue with the result, start a new calculation, or exit.
Ensures user inputs are validated to maintain program integrity.
