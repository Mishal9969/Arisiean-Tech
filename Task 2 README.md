Simple Calculator Project
Overview
This is a basic calculator project built using HTML, CSS, and JavaScript. The calculator can perform the following basic arithmetic operations:

Addition
Subtraction
Multiplication
Division
The calculator provides a simple user interface (UI) with buttons for entering numbers and operators, as well as a display screen that shows the result of the calculations.

Features:
Responsive design: The calculator adapts to different screen sizes.
Clear button: A C button that resets the display and clears the current calculation.
Delete button: A DEL button that removes the last digit or operator entered.
Error handling: Displays "Error" if an invalid operation (e.g., division by zero) is attempted.
Basic functionalities: Includes buttons for all digits (0-9), arithmetic operations (+, -, *, /), decimal point (.), and an equals (=) button to evaluate the expression.
Files
index.html: The main HTML file that defines the structure of the calculator.
style.css: The CSS file that styles the layout and appearance of the calculator.
script.js: The JavaScript file that handles the logic and functionality of the calculator, such as updating the display, clearing inputs, deleting digits, and evaluating expressions.
Code Explanation
1. HTML (index.html)
The structure of the calculator is defined using HTML. It includes:

A div element with the class calculator which acts as the main container.
A div with the class display to show the entered numbers and results.
A grid of buttons representing digits, arithmetic operators, and special functions like C (Clear) and DEL (Delete).
2. CSS (style.css)
The design of the calculator is handled by CSS:

The calculator container is centered in the viewport using Flexbox.
The buttons are arranged using CSS Grid to create a clean and organized layout.
Custom styles are applied for hover effects, and specific buttons (like = and C) have distinct colors for better usability.
3. JavaScript (script.js)
The logic behind the calculator's functionality is implemented in JavaScript:

appendNumber(): Adds a digit to the current expression displayed.
appendSymbol(): Adds arithmetic operators or a decimal point.
clearDisplay(): Resets the calculator display to its initial state.
deleteDigit(): Deletes the last entered digit or symbol from the current expression.
calculate(): Evaluates the expression entered using the eval() function, and displays the result. If an error occurs, an "Error" message is shown.
