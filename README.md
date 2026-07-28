# 💰 Smart Expense Tracker Application

A simple **Python-based Smart Expense Tracker** that allows users to record, manage, analyze, and visualize their daily expenses. The application uses **Python**, **NumPy**, **Pandas**, **Matplotlib**, and **Seaborn** to perform expense management, data analysis, and financial visualization.

---

## 📌 Features

### 1. Expense Input & Validation
- Accepts user input for:
  - Date (YYYY-MM-DD)
  - Amount
  - Category
  - Description
- Validates:
  - Amount must be greater than 0.
  - Category must be one of the following:
    - Food
    - Transport
    - Utilities
    - Entertainment
- Stores the entered expenses in a list.

---

### 2. Expense Tracker (Object-Oriented Programming)

Implements an `ExpenseTracker` class with the following methods:

- **add_expense()**
  - Adds a new expense to the existing `expenses.csv` dataset.

- **get_summary()**
  - Calculates:
    - Total Expenses
    - Average Expenses

- **filter_data()**
  - Displays expenses based on the selected category.

- **display_summary()**
  - Displays the total and average expenses.

---

### 3. Expense Analysis (NumPy & Pandas)

Uses **NumPy** and **Pandas** to perform financial analysis.

#### NumPy
- Calculate average spending
- Calculate total expenses
- Calculate total expenses per category

#### Pandas
- Load CSV dataset
- Check missing values
- Remove missing values
- Group expenses by category
- Group expenses by month
- Identify the top spending category
- Identify the top spending month

---

### 4. Data Visualization

Generates graphical reports using **Matplotlib** and **Seaborn**.

- 📊 Bar Chart
  - Total expenses by category

- 📈 Histogram
  - Frequency distribution of expense amounts

---

## 🛠 Technologies Used

- Python 3.x
- NumPy
- Pandas
- Matplotlib
- Seaborn

---

## 📂 Project Structure

```
Smart-Expense-Tracker/
│
├── expenses.csv          # Expense dataset
├── smart_expense.py      # Main Python program
└── README.md
```

---

## 📋 Dataset

The application uses a CSV file named **expenses.csv** with the following columns:

| Column | Description |
|---------|-------------|
| Date | Expense Date (YYYY-MM-DD) |
| Amount | Expense Amount |
| Category | Food, Transport, Utilities, Entertainment |
| Description | Details about the expense |

---

## ▶️ How to Run

### Step 1

Install the required libraries.

```bash
pip install numpy pandas matplotlib seaborn
```

### Step 2

Place the **expenses.csv** file in the same directory as the Python program.

### Step 3

Run the program.

```bash
python smart_expense.py
```

---

## 📷 Output

The application provides:

- Expense entry and validation
- Expense summary
- Expense filtering by category
- Total and average expense calculations
- Monthly expense analysis
- Category-wise expense analysis
- Top spending category
- Top spending month
- Bar Chart
- Histogram

---

## 📚 Python Concepts Used

- Variables
- Lists
- Loops
- Conditional Statements
- Functions
- Classes & Objects (OOP)
- File Handling (CSV)
- NumPy Arrays
- Pandas DataFrames
- Data Analysis
- Data Visualization

---

## 🎯 Learning Outcomes

This project demonstrates how to:

- Validate user input
- Store and manage expense records
- Perform numerical analysis using NumPy
- Analyze datasets using Pandas
- Apply Object-Oriented Programming concepts
- Create visual reports using Matplotlib and Seaborn
- Work with CSV datasets

---

## 👨‍💻 Author

**Maahroof Munshi**

MCA Student | Aspiring Data Analyst
