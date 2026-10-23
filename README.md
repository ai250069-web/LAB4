BIC21203 Lab 4a: Client-Side Scripting (JavaScript)

Name: Adam Shahputra bin Halim  
Matric Number: AI250069  
Course: BIC21203 Web Development

Introduction

This lab focuses on learning JavaScript functions, event handling, conditions, loops, and DOM manipulation. The purpose is to create interactive web pages using HTML and JavaScript.

Question 1: Interactive Text Changer

This question demonstrates how to change paragraph text when a user clicks a button.

How to run:
1. Open q1.html in your browser.
2. Initial Display: The page shows the default heading/paragraph text: “Welcome to my website!” above the “Change Message” button.
3. Click the “Change Message” button.
4. Expected Output: The paragraph text immediately updates to “Hello there!” via DOM text content manipulation.
   
Concepts used:
- JavaScript functions
- DOM selection using `getElementById()`
- Event handling using `addEventListener()`
- Changing text using `textContent`

Question 2: Smart Number Validator

This question checks the number entered by the user and displays a suitable validation message.

How to run:
1. Open q2.html in your browser.
2. Enter a value into the input field and click the “Check” button.
3. Expected Outputs based on test cases:
 • Input < 10 (e.g., 5): Displays “The number is lower than 10”.
 • Input > 10 (e.g., 15): Displays “The number is higher than 10”.
 • Input == 10 (e.g., 10 or 10.0):Displays “The number is equal to 10”.
 • Non-numeric input (e.g., abc):Displays “Please enter a valid number!”.
 • Empty / Whitespace input:Displays “Please enter a valid number!”.

Concepts used:
- Reading user input
- Input validation
- `if...else if...else` conditions
- Converting strings to numbers
- Displaying results using `textContent`

Test cases:
- 5: The number is lower than 10
- 10: The number is equal to 10
- 15: The number is higher than 10
- abc: Please enter a valid number!
- Empty input: Please enter a valid number!
- 10.5: The number is higher than 10

Question 3: Dynamic Number Generator

This question generates an ordered list containing numbers from 1 to 5 when the user clicks the Generate button.

How to run:
1. Open q3.html in your browser.
2. Initial Display: Only the “Generate”button is visible with an empty ordered list area.
3. Click the “Generate” button.
4. Expected Output: An ordered list (<ol>) dynamically populates with five list items (<li>) numbered sequentially:
 • The number is 1
 • The number is 2
 • The number is 3
 • The number is 4
 • The number is 5
5. Clicking the button repeatedly clears the previous list first, ensuring it consistently displays only five items without duplicates.

Concepts used:
- JavaScript functions
- `for` loops
- Creating HTML elements using `document.createElement()`
- Setting text using `textContent`
- Adding elements using `appendChild()`
- Clearing existing list items before generating again

Test Evidence

Question 1:
<img width="479" height="183" alt="image" src="https://github.com/user-attachments/assets/c4678732-d362-46e8-9225-52f4fd2c0103" />
<img width="494" height="179" alt="image" src="https://github.com/user-attachments/assets/40377806-34a0-45c8-8018-27ab5c3a2ab4" />

Question 2:
<img width="515" height="176" alt="image" src="https://github.com/user-attachments/assets/0d5b1810-8ae6-441c-96d7-dd4ebaf52cf5" />
<img width="442" height="202" alt="image" src="https://github.com/user-attachments/assets/cb93f530-4452-41a3-8d7e-ba4116489bcb" />
<img width="465" height="206" alt="image" src="https://github.com/user-attachments/assets/05196979-d3d1-40b1-a2cc-1b7d214c0e6b" />
<img width="504" height="196" alt="image" src="https://github.com/user-attachments/assets/5683a4e9-e0c6-40d0-a44d-2f3766f59b39" />
<img width="470" height="214" alt="image" src="https://github.com/user-attachments/assets/1986744a-4aed-4a6d-beab-8394987ddbb7" />
<img width="483" height="206" alt="image" src="https://github.com/user-attachments/assets/dd952d4f-d280-4e5f-ac1c-8337ddba0acf" />

Question 3:
<img width="902" height="516" alt="image" src="https://github.com/user-attachments/assets/fdb70ad9-f8c5-42c4-86c1-4ddd24e3eddb" />
