# CalculatorApp
A lightweight and responsive calculator built using HTML, CSS, and JavaScript. This project demonstrates the basics of front-end web development, including DOM manipulation and event handling. Perfect for beginners learning web development!</br></br>
![CalculatorApp Screenshot](https://github.com/user-attachments/assets/f2fdfce3-4732-42fb-add2-b7f638413825)

## Features</br>
- **Basic Arithmetic** Operations: Perform addition, subtraction, multiplication, and division.
- **Percentage Calculation**: Easily calculate percentages.
- **Clear and Delete Functionality**: Reset the calculator (AC) or delete the last digit (DEL).
- **Responsive Design**: Works seamlessly on both mobile and desktop devices.
- **Clean Interface**: Simple and user-friendly design.

## Technologies Used</br>
- **HTML (index.html)** :
The structure of the calculator is defined here, including the display input and buttons for digits, operators, and special functions (AC, DEL, %, =).
- **CSS (style.css)** :
Styling for the calculator, including layout, colors, and responsive design.
Uses Google Fonts (Poppins) for a modern look.
- **JavaScript (script.js)** :
Handles the logic for button clicks and calculations.
Supports basic arithmetic operations, percentage calculations, and clear/delete functionality.

## How It Works</br>
- **Button Clicks**: Each button has a data-value attribute that corresponds to its value (e.g., 1, +, AC).</br>
When a button is clicked, the calculate() function is called with the button's value as an argument.</br>
- **Display Update**: The display is updated dynamically based on the button clicked.
Special characters (%, AC, DEL, =) are handled separately.</br>
- **Calculation**: The eval() function is used to evaluate the mathematical expression in the display.</br>
For percentages, % is replaced with /100 before evaluation.
