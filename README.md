🧮 Calculator Web App

A simple browser-based calculator built using HTML, CSS, and JavaScript.
The calculator allows users to perform basic arithmetic operations using clickable buttons and displays results instantly.

📌 Project Description

This project implements a functional calculator interface with a display screen and a grid of buttons. Users can input numbers and operators, clear the display, delete the last character, and compute results.

The calculator logic is handled entirely on the client side using JavaScript.

🛠️ Technologies Used

HTML5 — Structure and layout

CSS3 — Styling and grid layout

JavaScript — Calculator functionality and logic

📂 Project Structure
calculator/
│
├── index.html      → Main calculator layout
├── styles.css      → Calculator styles
└── script.js       → Calculator logic

🧱 Features

✅ Number input buttons (0–9)

✅ Arithmetic operators (+ − × ÷)

✅ Decimal support

✅ Clear display button (C)

✅ Delete last character button (←)

✅ Evaluate expression (=)

✅ Grid-based button layout

✅ Disabled manual typing in display

🖥️ User Interface Components
Display Screen

Shows numbers and expressions

Right-aligned like a real calculator

Input is disabled to prevent keyboard typing

Updated only through button clicks

Buttons Grid

Buttons are arranged using CSS Grid into 4 columns for a clean calculator layout.

⚙️ JavaScript Functions
appendToDisplay(value)

Adds a number or operator to the display.

appendToDisplay('7')

clearDisplay()

Clears all text from the display.

Triggered by:

C button

deleteLast()

Removes the last entered character from the display.

Example:

123+ → 123

calculateResult()

Evaluates the expression in the display and shows the result.

Example:

2+3*4 → 14


Note: Uses eval() for expression evaluation. Suitable for small projects but not recommended for secure production apps.

▶️ How to Run

Download or clone the project

Open index.html in a web browser

Click calculator buttons to perform operations

🧪 Testing Checklist

Click numbers → appear on display

Click operators → appear correctly

Click C → display clears

Click ← → last character removed

Click = → correct result shown

Refresh page → calculator resets

🚀 Possible Improvements

Keyboard input support

Error handling for invalid expressions

Scientific calculator functions

Calculation history

Responsive mobile design

Replace eval() with a safer parser

📄 License

This project is for educational purposes.
