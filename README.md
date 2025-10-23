# ICS-Quadratic-Grader-Msoni-Deborah
#ICS Quadratic Grader
# ICS Quadratic Grader

This project is a single-page web application that combines two main functionalities:
1. A **Quadratic Equation Solver**
2. A **Grading System**

It was developed as part of the **ICT251 JavaScript GitHub Activity**, showcasing practical use of HTML and JavaScript to perform mathematical calculations and logical decision-making on a web page.

---

##  Quadratic Solver

The quadratic solver accepts three numeric inputs for **a**, **b**, and **c** and performs the following:

- Validates input values (ensures a ≠ 0 and all inputs are valid numbers)
- Calculates the **discriminant (D = b² − 4ac)**
- Determines the **nature of roots**:
  - D > 0 → Two distinct real roots  
  - D = 0 → One repeated real root  
  - D < 0 → Two complex conjugate roots  
- Displays the results clearly and neatly formatted
- Includes a **Reset** button to clear all input and output fields

---

## 🧾 Grading System

The grading system accepts a **score (0–100)** and determines the corresponding letter grade according to the following scale:

| **Grade** | **Range** |
|------------|-----------|
| A+ | 85–100 |
| A  | 75–84  |
| B+ | 65–74  |
| B  | 60–64  |
| C+ | 55–59  |
| C  | 50–54  |
| D  | 0–49   |

It outputs a message such as:

> “Score 82 → Grade A”

Edge cases (like exact boundaries, e.g., 85, 75, 65) are handled correctly.

---

## ⚙️ Technologies Used

- **HTML5** — Structure and layout  
- **JavaScript (ES6)** — Input validation, calculations, and output display  
- **CSS3** *(optional)* — For better page formatting and readability  
- **GitHub** — For version control and project hosting

---

##  How to Run

1. Open the file **`index.htm`** in any modern web browser.  
2. Enter values for **a**, **b**, and **c** to calculate the discriminant and nature of roots.  
3. Enter a **score** to determine the corresponding letter grade.  
4. Click **Reset** to clear the form and start again.

---





