Web Development Lab 4a

Student Information

- Name: MAISARAH BINTI MOHD NOR AKMAL
- Number Matrix: DI240071
- Subject: Web Development (BIC21203)
- Assignment: HTML5 and JavaScript

---

Introduction

This repository contains my Web Development assignment, which consists of three practical exercises developed using HTML5 and JavaScript.

The purpose of this assignment is to demonstrate my understanding of JavaScript functions, DOM manipulation, event listeners, conditional statements, loops and dynamic HTML elements.

Each question is developed independently using an HTML file ("index.html") and an external JavaScript file ("script.js").

---

Question 1 – Interactive Text Changer

Description

This webpage demonstrates how JavaScript can change the text of an HTML paragraph when a user clicks a button.

When the user clicks the Change Message button, the original message "Welcome to my website!" changes to "Hello there!".

Concepts Used

- DOM selection using "getElementById()"
- JavaScript functions
- "textContent"
- "addEventListener()"

Instructions to Run

1. Open the "Question1" folder.
2. Open "index.html" using a web browser.
3. The original welcome message will appear.
4. Click the Change Message button.
5. The paragraph should change to "Hello there!".


---

Question 2 – Smart Number Validator

Description

This webpage allows users to enter a number and checks whether it is lower than, higher than or equal to 10.

It also validates the input and displays an error message if the user enters invalid text or leaves the input empty.

Concepts Used

- DOM selection
- JavaScript functions
- Input validation
- Number conversion using "Number()"
- Conditional statements ("if...else if...else")
- "textContent"
- "addEventListener()"

Instructions to Run

1. Open the "Question2" folder.
2. Open "index.html" using a web browser.
3. Enter a number into the input field.
4. Click the Check button.
5. The appropriate validation message will appear below the input.

Test Cases

Input| Expected Result
5| The number is lower than 10
10| The number is equal to 10
15| The number is higher than 10
abc| Please enter a valid number!
Empty input| Please enter a valid number!
10.5| The number is higher than 10


---

Question 3 – Dynamic Number Generator

Description

This webpage generates an ordered list containing numbers from 1 to 5 when the user clicks the Generate button.

Each number is created dynamically as a new HTML list item. Existing list items are cleared before generating the list again to prevent duplication.

Concepts Used

- JavaScript functions
- "for" loops
- "document.createElement()"
- "textContent"
- "appendChild()"
- "addEventListener()"
- DOM manipulation

Instructions to Run

1. Open the "Question3" folder.
2. Open "index.html" using a web browser.
3. Click the Generate button.
4. An ordered list containing five items will appear.
5. Click the button again to verify that duplicate items are not created.

Expected Output

1. The number is 1
2. The number is 2
3. The number is 3
4. The number is 4
5. The number is 5

