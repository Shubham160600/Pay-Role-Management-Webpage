# Pay Role Management Webpage

A simple webpage to calculate the minimum number of currency notes to return as change for a given bill amount and cash given.

## Description

This webpage takes the bill amount and the cash given by the customer as input and calculates the minimum number of notes required to return as change. It displays the breakdown of the change in a table format.

## Output:

![image](https://github.com/user-attachments/assets/860d40d0-d37a-4ab7-a247-e0a16db82734)

## Features

*   Calculates the minimum number of notes for change.
*   Handles invalid input such as negative bill amounts or insufficient cash.
*   Displays the result in a user-friendly table.

## Technologies Used

*   HTML
*   CSS
*   JavaScript

## How to Use

1.  Open the `index.html` file in your web browser.
2.  Enter the bill amount in the "Enter the bill amount" field.
3.  Enter the cash given by the customer in the "Cash Given" field.
4.  Click the "Check" button.
5.  The table will display the number of notes to return for each denomination.

## HTML Structure

The HTML structure consists of:

*   A container `div` to hold all the elements.
*   A header with the title "Pay Role Management".
*   A paragraph describing the functionality of the page.
*   Input fields for the bill amount and cash given.
*   A button to trigger the calculation.
*   A table to display the change breakdown.

## CSS Styling

The CSS styles are embedded in the `<head>` section and include:

*   Basic styling for the container, input fields, button, and table.
*   Flexbox layout for the container.
*   Styling for the table elements to display borders.

## JavaScript Logic

The JavaScript code handles the following:

*   Retrieving the input values for the bill amount and cash given.
*   Validating the input to ensure the bill amount is positive and the cash given is sufficient.
*   Calculating the number of notes for each denomination.
*   Displaying the calculated notes in the table.
*   Displaying error messages for invalid input.

## JavaScript Functionality

*   **`errorHandle(error)`**: Displays an error message on the page.
*   **`hideMessage()`**: Hides the error message.
*   **`clickHandler()`**: This function is called when the "Check" button is clicked. It performs the following steps:
    *   Hides any previous error messages.
    *   Validates the input values.
    *   Calculates the remaining amount to be returned.
    *   Calculates the number of notes for each denomination.
    *   Updates the table with the calculated values.

## Improvements

*   Add more robust input validation.
*   Improve the user interface and styling (e.g., consider a more visually appealing color scheme than the current aqua background).
*   Make the note denominations configurable.
*   Consider using a more modern JavaScript framework.
*   Enhance error handling to provide more specific feedback to the user. For instance, if the cash given is insufficient, display the amount still needed.
*   Add clear labels and formatting to the input fields.
*   Improve the responsiveness of the webpage for different screen sizes.

## License

MIT Open Source License

## Author

Shubham Saurabh


