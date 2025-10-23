# ICS-Quadratic-Grader-Muntanga-Hamusonde

## 📘 Description
This is a single-page web application that:
1. Solves any quadratic equation of the form **ax² + bx + c = 0**.
2. Converts a numeric score (0–100) to a letter grade based on a given grading scale.

## 🚀 How to Run
1. Download or clone this repository.
2. Open `index.html` in any modern web browser.
3. The app works fully offline.

## 🧮 Test Cases

### Quadratic Solver
| Input (a, b, c) | Expected Output |
|-----------------|----------------|
| 1, -3, 2        | D = 1, Two real roots (x₁=2, x₂=1) |
| 1, 2, 1         | D = 0, One real root (x=-1) |
| 1, 2, 5         | D < 0, Complex roots |

### Grade Converter
| Score | Expected Grade |
|-------|----------------|
| 100   | A+ |
| 85    | A+ |
| 75    | A |
| 65    | B+ |
| 60    | B |
| 55    | C+ |
| 50    | C |
| 49    | D |
| 0     | D |
