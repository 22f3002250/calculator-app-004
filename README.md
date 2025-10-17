# Simple Calculator

## Overview
A lightweight, accessible web calculator that performs the four basic arithmetic operations: addition, subtraction, multiplication, and division. It features a clean UI, responsive layout, keyboard shortcuts, and clear error handling (e.g., division by zero).

Key features:
- Operations: +, -, ×, ÷
- Keyboard shortcuts: +, -, *, / and Enter to repeat last operation
- Floating-point result formatting to reduce precision noise
- Accessible labels and live result announcements

License: MIT

## Setup
No build tools or dependencies required.

Option 1: Open directly
- Double-click index.html to open it in your browser.

Option 2: Serve locally (recommended for best experience)
- Using Python 3:
  - cd into the project folder
  - Run: python -m http.server 8000
  - Open: http://localhost:8000

- Using Node (serve):
  - npm i -g serve
  - serve .
  - Open the provided local URL.

## Usage
1. Enter two numbers in the “First number” and “Second number” fields.
2. Click one of the operation buttons (+, −, ×, ÷) to compute.
3. Use keyboard shortcuts:
   - Press +, -, *, or / anywhere on the page to compute with that operation.
   - Press Enter to repeat the last operation.
4. Click “Clear” to reset inputs and the result.

Examples:
- 12.5 + 3 → 15.5
- 10 / 0 → Error: division by zero.

## License
MIT License

Copyright (c) 2025 SimpleCalc

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the “Software”), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.