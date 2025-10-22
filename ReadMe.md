# C Terminal Calculator & Encoder

This project is a **terminal-based calculator and encoder/decoder** program written in C.  
It combines a simple calculator, a scientific calculator, equation solvers, and text encoding/decoding, all while saving a history of operations to a file.

---

## Main Functions

### 1. Simple Calculator
Performs basic arithmetic operations:

- Addition
- Subtraction
- Multiplication
- Division
- Modulus

---

### 2. Scientific Calculator
Performs advanced mathematical operations:

- Square root of a real number
- Cubic root of a real number
- Absolute value of a number
- \( e^x \)
- Prime factorization of integers
- Factorial (integer, up to 20)
- Logarithm (base 10)
- Natural logarithm
- Real number raised to a real number
- Trigonometric functions: sin, cos, tan
- Inverse trigonometric functions (sin⁻¹, cos⁻¹, tan⁻¹)
- Shifted sin, cos, tan
- Solve first-degree equations \( y = ax + c \)
- Solve second-degree equations \( y = ax^2 + bx + c \)
- Summation of multiple numbers
- Multiplication of multiple numbers

---

### 3. Encoding & Decoding
- Encodes a word by shifting characters.
  - Characters from `a` to `x` and `A` to `X` are shifted by `+2`.
  - Characters `y`, `z`, `Y`, `Z` are wrapped around (`-24`).
- Decodes back to the original string.
- Uses dynamic memory allocation for strings.

---

### 4. File Operations
- Stores history of mathematical operations in `file.txt`.
- Display the stored data.
- Clear all stored history.

---

## Program Structure

### Libraries Used
```c
#include <stdio.h>
#include <stdlib.h>
#include <math.h>
#include <string.h>
