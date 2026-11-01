# Student Record Management System 🎓📊

A Python-based command-line application designed to input, manage, and analyze student academic records, grades, and performance metrics.

---

## 📋 Features

* **Dynamic Record Creation:** Input multiple student profiles along with custom student IDs, names, and subject marks.
* **Input Validation:** Built-in error handling to ensure student marks remain within the valid range of `0` to `100`.
* **Automated Calculations:** Automatically computes total marks, average scores, and assigns appropriate letter grades:
  * **Distinction:** Average $\ge$ 75
  * **First Division:** Average $\ge$ 60
  * **Pass:** Average $\ge$ 40
  * **Fail:** Average $<$ 40
* **Class Analytics:** 
  * Computes overall **class average** using `map` and `lambda` expressions.
  * Identifies **high performers** (students with an average $\ge$ 75).
* **Python Concept Demonstrations:** Includes implementations for positional/keyword arguments, `*args`, default parameters, recursion, and variable scopes.

---

## 🚀 Getting Started

### Prerequisites
Make sure you have **Python 3.x** installed on your machine.

### Running the Application
1. Clone the repository or download the `miniproject4` file.
2. Open your terminal or command prompt.
3. Run the script using the following command:
   ```bash
   python miniproject4
