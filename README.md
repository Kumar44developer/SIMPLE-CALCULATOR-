# 🧮 Simple Calculator

A lightweight, browser-based calculator built entirely in a single HTML file using vanilla HTML and JavaScript. It performs basic arithmetic operations with a clean button-grid interface — no frameworks, no dependencies, no setup required.

---

## Features

- Addition, subtraction, multiplication, and division
- Chained calculations using multiple operators
- Smart operator replacement — pressing a new operator overwrites the previous one instead of stacking
- Clear button to reset the display
- Expression evaluation with the equals button
- Works instantly in any modern browser

---

## Tech Stack

| Technology  | Purpose                        |
| ----------- | ------------------------------ |
| HTML5       | Page structure and button grid |
| JavaScript  | Arithmetic logic and input handling |

---

## Project Structure

```
SIMPLE-CALCULATOR-/
└── index.html       # Complete calculator (markup + logic)
```

The entire application lives in a single file. The HTML form handles the button layout and display, while inline JavaScript functions manage operator input and expression evaluation.

---

## How It Works

The calculator uses a text input field as its display. Each number button appends its digit to the field. Operator buttons (`+`, `-`, `X`, `/`) call dedicated JavaScript functions that:

1. Check whether the last character is already an operator
2. Replace it if so, or append the new operator if not

The `=` button evaluates the full expression using JavaScript's `eval()` function and displays the result. The `C` button clears the display.

---

## Getting Started

No installation needed. Just open the file in a browser.

**Option 1 — Clone and open:**

```bash
git clone https://github.com/Kumar44developer/SIMPLE-CALCULATOR-.git
```

Then open `index.html` in any browser.

**Option 2 — Download:**

Download `index.html` directly from the repository and double-click to open.

---

## Button Layout

```
[ 1 ] [ 2 ] [ 3 ] [ + ]
[ 4 ] [ 5 ] [ 6 ] [ - ]
[ 7 ] [ 8 ] [ 9 ] [ X ]
[ C ] [ 0 ] [ = ] [ / ]
```

---

## Author

**Kumar44developer** — [GitHub Profile](https://github.com/Kumar44developer)
