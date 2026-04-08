# 🧪 PyTest Experiment: Unit Testing in Python

---

## 📌 Overview

This project demonstrates unit testing of Python functions using **PyTest**.  
It includes testing of basic mathematical operations, handling edge cases, exception handling, and parameterized testing.

---

## 🎯 Objectives

- Understand unit testing concepts  
- Write test cases using PyTest  
- Execute and analyze test results  
- Handle edge cases and exceptions  
- Use parameterized testing  

---

## 🛠️ Technologies Used

- Python 3.x  
- PyTest  

---

## 📂 Project Structure
.
├── pythondemo.py # Implementation of functions
├── test_pythondemo.py # Test cases using PyTest

---

## ⚙️ Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/your-username/pytest-experiment.git
cd pytest-experiment

2. Install dependencies
pip install pytest
3. Verify installation
pytest --version
Running the Tests
pytest -v
Functions Implemented
add(a, b) → Returns sum
subtract(a, b) → Returns difference
multiply(a, b) → Returns product
divide(a, b) → Raises exception when dividing by zero
is_even(num) → Checks whether a number is even
factorial(n) → Computes factorial with error handling
🔍 Test Coverage
✅ Functional Testing
Validates correctness of all operations
⚠️ Exception Handling
Division by zero
Negative input for factorial
🔄 Parameterized Testing
Multiple input combinations tested
🔍 Edge Cases
Factorial of 0 and 1
Even/odd number validation
📊 Sample Output
test_pythondemo.py::test_add PASSED
test_pythondemo.py::test_multiply_fail FAILED
test_pythondemo.py::test_divide_by_zero PASSED
test_pythondemo.py::test_is_even PASSED
test_pythondemo.py::test_add_param FAILED
test_pythondemo.py::test_factorial PASSED
test_pythondemo.py::test_factorial_negative PASSED
⚠️ Note

Some test cases are intentionally failing to demonstrate how PyTest identifies errors and reports failures.

🧠 Learning Outcomes
Learned how to write and execute unit tests
Understood debugging using test failures
Gained experience in handling edge cases
Explored parameterized and exception testing
👩‍💻 Author

Sasmita Das

⭐ Acknowledgement

This experiment was performed as part of the Open Source Technologies Lab.
