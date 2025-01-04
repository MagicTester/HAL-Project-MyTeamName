# How to Use the Simple Calculator

## Running the Calculator

1. **Clone the Repository**: First, clone the repository to your local machine using the following command:
    ```sh
    git clone <repository-url>
    ```

2. **Navigate to the Project Directory**: Change your directory to the project folder:
    ```sh
    cd <project-directory>
    ```

3. **Open the HTML File**: Open the `index.html` file located in the `assets` folder in your preferred web browser:
    ```sh
    open assets/index.html
    ```

## Using the Calculator

1. **Enter Numbers**: 
    - Enter the first number in the input field labeled "Enter first number".
    - Enter the second number in the input field labeled "Enter second number".

2. **Select Operation**: Click on the button corresponding to the arithmetic operation you want to perform:
    - **Add**: Adds the two numbers.
    - **Subtract**: Subtracts the second number from the first number.
    - **Multiply**: Multiplies the two numbers.
    - **Divide**: Divides the first number by the second number.

3. **View Result**: The result of the operation will be displayed below the buttons in the "Result" section.

## Example

1. Enter `5` in the "Enter first number" field.
2. Enter `3` in the "Enter second number" field.
3. Click the "Add" button.
4. The result `8` will be displayed in the "Result" section.

## Handling Errors

- **Division by Zero**: If you attempt to divide by zero, an error message "Division By Zero Error" will be logged to the console, and the result will not be displayed.

## Code Information

- The calculator performs basic arithmetic operations using JavaScript functions defined in separate files (`add.js`, `sub.js`, `mul.js`, `div.js`).
- The HTML file (`index.html`) provides the user interface for the calculator.