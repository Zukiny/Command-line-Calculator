# Simple Python Calculator

This is a basic command-line calculator built in Python. The calculator allows users to perform basic arithmetic operations like addition, subtraction, multiplication, and division.

## Features

- **Addition**: Adds two numbers.
- **Subtraction**: Subtracts the second number from the first.
- **Multiplication**: Multiplies two numbers.
- **Division**: Divides the first number by the second (includes error handling for division by zero).

## Functions Used

1. **`add(x, y)`**:
    - Takes two numbers as input and returns their sum.
    
2. **`subtract(x, y)`**:
    - Takes two numbers as input and returns the result of subtracting the second number from the first.
    
3. **`multiply(x, y)`**:
    - Takes two numbers as input and returns their product.
    
4. **`divide(x, y)`**:
    - Takes two numbers as input and returns the result of dividing the first number by the second.
    - Includes a check to prevent division by zero, returning an error message if attempted.

5. **`calculator()`**:
    - The main function that drives the calculator. It prompts the user to select an operation and input two numbers. Based on the user's choice, it calls the appropriate function and displays the result.

## How to Run the Program

### Prerequisites

- **Python 3.x** should be installed on your system. You can download Python from [here](https://www.python.org/downloads/).

### Running the Calculator

1. Clone the repository from GitHub to your local machine:
   ```bash
   git clone https://github.com/Zukiny/Command-line-Calculator.git
