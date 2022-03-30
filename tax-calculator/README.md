### Try to do the following with this exercise:

-   Understanding the DOM/document, and how a javascript file is imported and interacts with an HTML document.
-   Try to create a variable called `totalAmountWithTax` and assign that value to the `totalElementWithTax` element's innerHtml.
-   Try finishing the `calculateTotal` function by starting with the following:
    -   Create a new function called `calculateTax()`
    -   Find the element where calculate tax is displayed, assign a value of 0 to it the same way as the `totalWithTax` is displayed
    -   Create a function called `calculateSubtotal()`
        -   Use this function to calculate the sum of each item amount that is show on the screen. Return the result.
    -   Using the `calculateSubtotal()` function and its result, calculate the tax by multiplying their sum by the tax amount
        -   Make sure to use variables!
    -   Display the new calculated tax on the page.
    -   Going back to the `calculateTotals` function, practice calling a function again by calling the `calculateTax()` function to get the calculated tax.
    -   Add the calculated tax to the subtotal, and display the result on screen.
-   Bonus: Try modifying the calculateTax function to return a result based on a given `taxRate` parameter being passed to it.
