# NumPy for Data Science

A structured learning repository covering NumPy fundamentals and applied exercises using Python. This repository contains two Jupyter notebooks — one focused on core concepts with hands-on practice, and one dedicated to exercises built around real-world problem scenarios.

---

## Repository Structure

```
numpy-notes-and-practice/
│
├── Numpy_Python.ipynb       # Core concepts and practice notebook
├── Exercise_Numpy.ipynb     # Applied exercises and problem solving
└── README.md
```

---

## Notebooks Overview

### 1. Numpy_Python.ipynb — Core Concepts

A comprehensive practice notebook covering NumPy from the ground up.

**Topics Covered:**

- **Basic Array Creation** — Creating 1D and 2D arrays, understanding dtype upcasting, difference between Python lists and NumPy arrays
- **Array Generation Functions** — `np.arange()`, `np.zeros()`, `np.ones()`, `np.linspace()`, `np.eye()`, `np.random`
- **Array Indexing and Slicing** — Positive and negative indexing, slicing ranges, multi-dimensional access
- **Array Attributes** — `.shape`, `.ndim`, `.size`, `.dtype`
- **Reshaping** — `reshape()`, `flatten()`, `ravel()`
- **Broadcasting** — Scalar and array operations across dimensions
- **Aggregation Functions** — `np.sum()`, `np.mean()`, `np.min()`, `np.max()`, `np.std()`, axis-wise operations
- **Boolean Masking and Fancy Indexing** — Conditional filtering, masking with logical operators
- **Copy vs View** — Understanding shallow copy and `.copy()` to avoid unintended mutations
- **Matrix Operations** — Element-wise multiplication, dot product (`@` and `np.dot()`), transpose (`.T`)
- **Advanced Array Manipulation** — `np.vstack()`, `np.hstack()`, `np.column_stack()`, `np.hsplit()`, `np.vsplit()`

---

### 2. Exercise_Numpy.ipynb — Applied Exercises

A problem-solving notebook applying NumPy concepts to structured datasets and logic problems.

**Exercise 1 — Valid Sudoku Checker**

Validates a 9x9 Sudoku grid using NumPy array operations.

- Row-wise sum validation using `np.sum(s, axis=1)`
- Column-wise sum validation using `np.sum(s, axis=0)`
- 3x3 subgrid extraction and sum check using nested loops and 2D slicing
- Each row, column, and box must sum to 45 to be considered valid

**Exercise 2 — Student Marks Analysis**

Works with a structured 2D array representing student data (Age, Math Marks, Science Marks).

| Operation | NumPy Technique Used |
|---|---|
| Get matrix shape | `.shape` |
| Average age | `np.mean(data[:, 0])` |
| Extract subject column | `data[:, 1]` |
| Highest score in a subject | `np.max()` |
| Filter by condition | Boolean masking |
| Update marks in-place | In-place operations (`+=`) |
| Count students by age | `len()` with boolean filter |
| Column-wise average | `np.mean(axis=0)` |
| Multi-condition filtering | `&` operator with boolean arrays |
| Replace values conditionally | Boolean mask assignment |

---

## Tech Stack

- Python 3.13
- NumPy
- Jupyter Notebook

---

## Key Concepts Demonstrated

- Difference between NumPy arrays and Python lists
- Axis-based operations (axis=0 for columns, axis=1 for rows)
- In-place array modification vs copy-based operations
- Real-world application of boolean masking for data filtering
- Matrix arithmetic including dot product and transpose
- Stacking and splitting arrays for data manipulation

---


## Author

**Sai Halwai**
B.Sc. Computer Science (Game Design & Development)
Shree SaiBaba College, Shirdi

GitHub: [SAI01-05](https://github.com/SAI01-05)
Email: saihalwai01@gmail.com

---

## Related Projects

- [Python EDA — Apple iPhone Flipkart Dataset](https://github.com/SAI01-05/Python_Data_Analysis_Mini_Project)
- [Bank Loan Report Dashboard — Excel](https://github.com/SAI01-05/SAI01-05-bank-loan-report-excel-dashboard)
- [Netflix Content Analysis — MySQL](https://github.com/SAI01-05/DataScience_SQL_NetflixProject-2)
