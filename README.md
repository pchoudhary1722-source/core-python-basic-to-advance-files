# 🐍 Python Learning Journey — Priyanka

A collection of Jupyter notebooks documenting my step-by-step journey of learning **Python** — from the basics (variables, loops, functions) to **Object-Oriented Programming** and **data analysis libraries** (NumPy, Pandas, Matplotlib).

Each notebook contains short explanations, practice questions, and worked examples written while learning.

---

## 📚 Topics Covered

### 1. Python Basics
| Notebook | What's inside |
|---|---|
| `variables.ipynb` / `Untitled.ipynb` | Creating variables; int, float, string and boolean data types |
| `Untitled1.ipynb` | Type casting and string formatting (`.format()`, f-strings, `:.2f` precision) |
| `function of built.ipynb` | Built-in functions: `print`, `type`, `len`, `input`, `int`, `float`, `str`, `max`, `min`, `abs`, `round`, `sorted`, `list`, `enumerate` |

### 2. Data Structures
| Notebook | What's inside |
|---|---|
| `method of list.ipynb` | List and tuple methods (`append`, etc.) |
| `method of set.ipynb` | Set methods (`add`, `update`, `remove`, `union`, `intersection`, `difference`), dictionaries (`get`, `keys`, `values`, `items`), indexing, slicing and stepping |

### 3. Control Flow
| Notebook | What's inside |
|---|---|
| `for loop.ipynb` | `for` loops with `range()`, reverse counting, multiplication tables, and `while` loops |

### 4. Functions
| Notebook | What's inside |
|---|---|
| `user and define function.ipynb` | User-defined functions: basic, mathematical (area, simple interest, temperature conversion), logic (even/odd, largest of numbers, pass/fail), and real-life problems (salary, BMI, discount, bill, calculator) |
| `lambda.ipynb` | Lambda (anonymous) functions with `map()` and `filter()` |

### 5. Object-Oriented Programming (OOP)
| Notebook | What's inside |
|---|---|
| `oops.ipynb` | Classes and objects, `self`, constructors (`__init__`), and inheritance (single, multiple, multilevel, hierarchical) |
| `encapsulation.ipynb` | Public vs private members, accessing private data through methods |
| `method overloading.ipynb` | Method overriding, simulating method overloading with default arguments, `super()` with methods and `__init__` |
| `ATM_ (1).ipynb` | **Mini project** — a console ATM simulator built with a class (create/change PIN, check balance, withdraw money) |

### 6. Modules & Packages
| File | What's inside |
|---|---|
| `priyaaa/priya.py` | A custom module with an `average()` function and a few variables |
| `abc.ipynb` | Importing and using the custom module (`from priyaaa import priya`) |

### 7. Data Analysis Libraries (`libary/`)
| Notebook | What's inside |
|---|---|
| `numpy.ipynb` | 1D–4D arrays, `reshape`, `flatten`, `ravel`, indexing / slicing / stepping, boolean indexing, `insert` / `delete`, and mathematical functions |
| `pandas.ipynb` | Building DataFrames from dictionaries; reading and working with CSV / Excel data |
| `matplotlib.ipynb` | Line chart, bar chart, histogram, scatter plot, pie chart, box plot and heatmap |

---

## 🗂️ Repository Structure

```
priyanka/
├── variables.ipynb
├── Untitled.ipynb
├── Untitled1.ipynb
├── Untitled3.ipynb
├── function of built.ipynb
├── user and define function.ipynb
├── lambda.ipynb
├── for loop.ipynb
├── method of list.ipynb
├── method of set.ipynb
├── oops.ipynb
├── encapsulation.ipynb
├── method overloading.ipynb
├── ATM_ (1).ipynb
├── abc.ipynb
├── DATA.xlsx              # Personal investment sheet
├── priyaaa/
│   └── priya.py           # Custom Python module
└── libary/
    ├── numpy.ipynb
    ├── pandas.ipynb
    ├── matplotlib.ipynb
    ├── st.csv             # Sample student marks data (with missing/dirty values)
    ├── st11.csv
    └── hel.xlsx           # Sample student data (Excel)
```

---

## 🛠️ Requirements

- Python 3.x
- Jupyter Notebook or JupyterLab
- Libraries:
  ```bash
  pip install numpy pandas matplotlib openpyxl
  ```

---

## ▶️ How to Run

1. Clone the repository
   ```bash
   git clone https://github.com/<your-username>/<your-repo-name>.git
   cd <your-repo-name>
   ```
2. Install the requirements (see above)
3. Launch Jupyter
   ```bash
   jupyter notebook
   ```
4. Open any `.ipynb` file and run the cells.

> 💡 To use the custom module in `abc.ipynb`, run the notebook from the repository root so that `priyaaa/` can be imported.

---

## 🎯 Learning Goals

- Build a strong foundation in core Python
- Understand OOP concepts through real-world examples (ATM, bank, student)
- Practice data handling, cleaning and visualization with NumPy, Pandas and Matplotlib

---

## 👩‍💻 Author

**Priyanka**
Feel free to ⭐ the repo if you find it helpful!

---

## 📄 License

This project is for learning purposes. Feel free to use and modify it.
