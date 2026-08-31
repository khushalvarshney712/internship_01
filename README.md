# Python Utilities & ATM Simulator

A beginner-friendly Python console application that combines several useful Python programs into one menu-driven utility.

This project was created to practice fundamental Python programming concepts such as functions, loops, conditional statements, lists, user input, and basic problem-solving.

## Features

The application provides the following utilities:

### 1. Temperature Converter

* Celsius → Fahrenheit
* Fahrenheit → Celsius

### 2. Student Grade Calculator

* Takes marks for multiple subjects
* Calculates average marks
* Assigns a grade based on the average

### 3. Even/Odd & Prime Number Checker

* Checks whether a number is even or odd
* Checks whether a number is prime

### 4. ATM Simulator

* PIN-based login
* Check account balance
* Deposit money
* Withdraw money
* Prevents withdrawal when the balance is insufficient
* Allows the user to exit the ATM

##  Technologies Used

* Python 3
* Built-in Python functions and modules
* No external libraries required

## Python Concepts Practiced

This project helped practice:

* Variables and data types
* `input()` and `print()`
* `if`, `elif`, and `else`
* `for` and `while` loops
* Functions
* Function arguments and return values
* Lists
* String formatting
* Arithmetic and comparison operators
* Basic input validation
* Menu-driven programs

##  Project Structure

```text
python-utilities/
│
├── python_utilities.py
├── README.md
└── .gitignore
```

## How to Run

### 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_LINK
```

### 2. Open the project folder

```bash
cd python-utilities
```

### 3. Run the program

```bash
python3 python_utilities.py
```

## ATM Simulator

The ATM simulator uses a simple PIN-based login system.

For demonstration purposes, the default PIN is:

```text
1234
```

The initial balance is:

```text
$1000.00
```

> Note: This is an educational console project and does not represent a real banking system.
>
>  Example Menu

```text
==================================================
WELCOME TO PYTHON UTILITIES!
==================================================

Choose a task:
1. Temperature Converter
2. Student Grade Calculator
3. Even/Odd & Prime Number Checker
4. Mini Project - ATM Simulator
5. Exit
```

##  Learning Objective

The main objective of this project is to strengthen Python fundamentals by combining multiple small programs into a single menu-driven application.

It also provides practice in breaking a problem into smaller functions and handling user input.

## Future Improvements

Possible improvements for future versions:

* Add better input validation
* Store ATM balance permanently using files
* Add transaction history
* Add multiple user accounts
* Add a graphical user interface
* Separate each utility into its own Python module

##  Author

**Khushal Varshney**

B.Tech – Electronics & Communication Engineering

This project was developed as part of my Python learning and practice.
