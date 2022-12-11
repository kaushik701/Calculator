This is the Simple User Friendly Calculator, made with HTML, CSS, JavaScript without any javascript framework.
A script.js file is written with that includes the basic functionality of every buttons of the calculator.
A script.css file is written with that includes the designing functionality of the calculator with various combination of colors.

In index.html file, the 'calculator-grid' class is used to represent the various buttons of the calculator which include numbers and artihmetic operators, in a single grid.

In script.js file, 'document.querySelectorAll' was only used for the numbers and operation buttons. Well, this is because these buttons appear several times on the calculator.

The first one is the clear() function, which will clear all the different variables. The next method is delete() for clearing a single number. A function that determines what will occur every time a user clicks on a number to add to the display called appendNumber(number). A chooseOperation(operation) function that controls what will happen anytime a user clicks on any operation button.
Another key function is compute(). It takes the values inside your calculator and displays the result.
Finally, a updateDisplay() function lets us update the values inside of the output.