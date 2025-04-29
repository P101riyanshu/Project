# Project
A simple and stylish calculator built using HTML, CSS, and JavaScript.
<------------------------------------For HTML--------------------------------------->
Title & File Links

1.<title>calculator</title>: Sets the page title in the browser tab.
2.<link rel="stylesheet" href="styles.css">: Links the external CSS file.
3.<script src="script.js"></script>: Links the external JavaScript file.

Main Container

1.<div id="calculator">: Wraps the entire calculator layout.
2.Display Field
3.<input type="text" id="display" disabled>:
4.Shows the current input or result.
5.Disabled to prevent direct typing.
6.Button Grid using Table
7.<table>: Organizes calculator buttons into rows and columns.
8.Button Elements
9.<button>: Represents calculator keys.
10.onclick="...": Calls JavaScript functions when clicked.
11.class="operator" or class="oparand": Used for styling different types of buttons.
12.Button Functionalities via Attributes
13.AC, DEL, Operators (+, -, *, /, %, .)
14.Numbers (0–9, 00)
15.= (Equal) to compute the result
<----------------------------------------In CSS------------------------------------------>

Feature	Description:-

1. linear-gradient	Background transitions from green shades for visual appeal
2.vh-units	Makes the calculator centered vertically across all screen sizes
3. box-shadow	Adds 3D-like depth to buttons and container
4. transition	Smooth hover animations for interactive feel
5. border-radius	Rounded corners for modern design
6. operator / .operand	Custom styling to differentiate operation buttons and number buttons

<-----------------------------In JavaScript--------------------------------------->
Main Functions:

1. appendToDisplay(value): Appends number or operator to the display.

2.clearDisplay(): Clears the entire display (AC button).

3.deleteLast(): Deletes the last character from the display (DEL button).

4.calculateResult(): Evaluates the entered expression using eval().