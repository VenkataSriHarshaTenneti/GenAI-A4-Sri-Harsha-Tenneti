# File Handling in Python – Read, Write, Append & Modes

## 📌 Project Overview

This project demonstrates basic file handling operations in Python, including creating files, writing data, reading file contents, appending new data, and handling missing files.

It also includes practical exercises using lists, dictionaries, loops, conditional statements, and basic calculations.

## 🛠️ Technologies Used

- Python 3.12
- Jupyter Notebook
- VS Code

## 📚 Tasks Covered

### Task 1 – Write Sales Records to a File
- Create a list of sales amounts.
- Open `sales_data.txt` in write mode.
- Write sales values in comma-separated format.
- Close and reopen the file.
- Read and print its contents.

### Task 2 – Read File in Different Ways
Demonstrates three file-reading methods:
- `read()` – Reads the entire file.
- `readline()` – Reads the first line.
- `split()` – Separates comma-separated values.
- Convert sales values into a list of integers.
- Clean up newline characters using `strip()`.

### Task 3 – Append New Sales
- Add new sales amounts to the existing file.
- Use append mode (`"a"`).
- Reopen and display the updated file.
- Count the total number of lines.

### Task 4 – Generate Summary Report from File
Read sales values from the file and calculate:
- Total sales
- Highest sale
- Lowest sale
- Average sale

Uses built-in Python functions such as `sum()`, `max()`, and `min()`.

### Task 5 – Create Product Information File
- Ask the user to enter three product names and prices.
- Store the information in `products.txt`.
- Display the saved product information with proper formatting.

### Task 6 – Read File Safely
- Ask the user to enter a filename.
- Check whether the file exists using `os.path.exists()`.
- Read and print the file if it exists.
- Display an appropriate message if the file is missing.

### Task 7 – Mini Project: Export Discounted Price
- Create a dictionary containing product names and prices.
- Ask the user for a discount percentage.
- Calculate discounted prices for each product.
- Export the report into `discount_report.txt`.
- Read the report and print it in the terminal.

The report also includes:
- Total number of products
- Average discounted price

## 📂 Files Generated

| File Name | Description |
|---|---|
| `sales_data.txt` | Stores sales records |
| `products.txt` | Stores product names and prices |
| `discount_report.txt` | Stores discounted prices and summary |

## ▶️ How to Run

1. Clone or download this project.
2. Open the project folder in VS Code.
3. Make sure Python 3.12 and the Jupyter extension are installed.
4. Open `A-4.ipynb`.
5. Select the Python kernel.
6. Run the notebook cells sequentially.

## 🧠 Python Concepts Practiced

- File handling (`open()`, `read()`, `write()`, `close()`)
- File modes (`r`, `w`, `a`)
- Lists and dictionaries
- Loops (`for`)
- Conditional statements (`if-else`)
- User input (`input()`)
- String formatting (f-strings)
- Type conversion (`int()`, `float()`)
- String methods (`strip()`, `split()`, `join()`)
- Basic mathematical calculations
- File existence checking using `os.path.exists()`

## 🎯 Learning Outcome

Through these exercises, I practiced handling text files in Python, storing and retrieving data, processing file contents, generating reports, and performing basic calculations using real-world examples.

---

**Author:** T.V.Sri Harsha  
**Language:** Python 3.12  
**Project Type:** Python File Operations
