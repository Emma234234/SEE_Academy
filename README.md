
# Simple Calculator Program

## Overview

This is a beginner-friendly Python program designed to perform basic arithmetic operations on two numbers provided by the user. It demonstrates fundamental programming concepts such as user input, type conversion, arithmetic calculations, and formatted output.

When you run the program, it greets you with "Hello World" and then asks for two numbers. These numbers can be whole numbers or decimals. The program then calculates and displays the sum, difference, product, and quotient of the two inputs.

## Features

- **User Input:** Accepts two numbers from the user via the command line.
- **Supports Decimals:** Uses Python's `float()` function to handle decimal numbers, allowing for more precise calculations.
- **Basic Arithmetic Operations:** Calculates addition, subtraction, multiplication, and division.
- **Clear Output:** Shows the results in an easy-to-read format with descriptive labels.
- **Straightforward Code:** Perfect for beginners to understand basic programming logic.

## How the Program Works

1. **Greeting:** Prints `"Hello World"` as an introductory message.
2. **Input Collection:** 
   - Prompts the user to enter the first number.
   - Prompts the user to enter the second number.
3. **Computation:**
   - Calculates the **sum** by adding the two numbers.
   - Calculates the **difference** by subtracting the second number from the first.
   - Calculates the **product** by multiplying the two numbers.
   - Calculates the **quotient** by dividing the first number by the second.
4. **Results Display:** Prints out the results of all calculations clearly labeled.

## Important Considerations

- **Decimal Inputs:** The program converts user inputs to floating-point numbers (`float`), so you can enter decimal values like `3.14` or `0.5`.
- **Division by Zero:** This version does not handle division by zero errors. Entering `0` as the second number will cause the program to crash. Use caution!
- **User Responsibility:** The program expects the user to enter valid numeric inputs; currently, it does not validate input types or catch potential errors.

## Example Usage

```
Enter the first number: 15.2
Enter the second number: 3
Results of your two numbers:
Sum: 18.2
Difference: 12.2
Product: 45.6
Quotient: 5.066666666666666
```

## How to Run the Program

1. Make sure Python is installed on your computer. You can download it from [python.org](https://www.python.org/downloads/).
2. Save the script to a file, for example `calculator.py`.
3. Open a terminal or command prompt.
4. Navigate to the directory containing `calculator.py`.
5. Run the program by typing:

```
python calculator.py
```

6. Follow the on-screen prompts to enter two numbers and view the results.

## Possible Improvements

- Add **input validation** to handle non-numeric inputs gracefully.
- Implement **error handling** for division by zero.
- Enhance the user interface with clearer messages or a menu system.
- Expand arithmetic capabilities (e.g., modulus, exponentiation).

```

