# Python Projects 02

A collection of **five practical, menu-driven console applications** built in Python. Designed for beginners and intermediate learners to practice core programming concepts like functions, dictionaries, sets, file I/O, error handling, and loops.

> This project originally runs as a [Google Colab](https://colab.research.google.com/) notebook (`Python_Project_02.ipynb`). You can open it directly in Colab or run each section locally with any Python 3 interpreter.

---

## Contents

| # | Project | Highlights |
|---|---------|------------|
| 1 | **Contact Book** | CRUD operations using a dictionary, search, edit & delete |
| 2 | **Ingredient Checker** | Recipe matching with sets (subset/missing/extra logic) |
| 3 | **Note-Taking App** | Persistent notes using file I/O (`notes.txt`), search & edit |
| 4 | **Safe Calculator** | Basic arithmetic + robust error handling |
| 5 | **Temperature Converter** | Celsius / Fahrenheit / Kelvin conversions |

---

## Getting Started

### Prerequisites

- **Python 3.x** — [download here](https://www.python.org/downloads/)
- (Optional) A Google account to run the `.ipynb` in [Colab](https://colab.research.google.com/)

### Running the Notebook

1. **On Colab** — go to the notebook page:
   ```
   https://colab.research.google.com/github/Plabon-Basak/python-projects-2
   ```
   Then run each cell with **Shift + Enter**.

2. **Locally** — open `Python_Project_02.ipynb` in Jupyter Notebook / JupyterLab, or copy a section into a `.py` file and run:
   ```bash
   python my_project.py
   ```

**Note:** The note-taking app creates a `notes.txt` file in the current directory to store your notes.

---

## Projects Overview

### 1. Contact Book 📇
A simple contact manager that stores contacts by name with phone and email.

- Show all contacts
- Add a new contact
- Search by name
- Edit an existing contact
- Delete a contact

### 2. Ingredient Checker 🍕
Given a recipe name and the ingredients you have, it tells you whether you can make the dish — showing **missing** and **extra** ingredients.

Recipes included:
`Pizza`, `Burger`, `Salad`, `Pasta`, `Soup`

### 3. Note-Taking App 📝
A persistent, file-based note manager.

- Show / Add / Search / Edit / Delete notes
- Data saved to `notes.txt`

### 4. Safe Calculator 🧮
A calculator wrapped in careful input validation.

- Addition, Subtraction, Multiplication, Division, Modulus
- Handles division by zero, invalid numbers, and unexpected errors

### 5. Temperature Converter 🌡️
Convert between Celsius, Fahrenheit, and Kelvin.

- 6 combinations of unit conversions
- Results formatted to 2 decimal places

---

## Concepts Practiced

- Functions & modular design
- Dictionaries and sets
- String processing (`title()`, `strip()`, `split()`)
- File read/write (`open()`, with-context manager)
- `try` / `except` / `finally` error handling
- Infinite loops with `while True` + menus

---

## License

This project is for educational purposes. Feel free to use, modify, and share it.

---

Made with ❤️ by **Plabon Basak** — [GitHub](https://github.com/Plabon-Basak)
