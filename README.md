# Calculator

A basic calculator built as part of my Web Development Internship (Level 1, Task 3). Built entirely with vanilla HTML, CSS, and JavaScript — no libraries or frameworks.

## 🌐 Live Preview
Open `index.html` in any browser to use.

## 🛠️ Built With
- HTML5
- CSS3 (CSS Grid for button layout)
- Vanilla JavaScript (event listeners, DOM manipulation, conditional logic)

## ✨ Features
- Addition, subtraction, multiplication, division, and modulo (%)
- Live display of current input and running expression
- Delete last digit (DEL) and clear all (AC)
- Full keyboard support (numbers, operators, Enter, Backspace, Escape)
- Division-by-zero handling
- Responsive, dark-themed UI with hover and press animations

## ⚙️ How It Works
- Number and operator buttons update `currentOperand` and `previousOperand` via event handlers
- `chooseOperator()` locks in the pending operation and preps the display for the next number
- `calculate()` parses both operands, applies the chosen operator with a `switch` statement, and rounds the result to avoid floating-point errors
- A `keydown` listener mirrors all button actions for keyboard use

## 📂 File Structure
Single-file build — HTML, CSS, and JS are all combined in `index.html` for simplicity and portability.

## 📌 About This Project
Completed as part of a web development internship task focused on applying JavaScript fundamentals — event handling, conditional logic, and DOM updates — alongside CSS Grid for layout.
