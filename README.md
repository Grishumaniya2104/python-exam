# 🧑‍💻 Interactive Personal Data Collector

## 📌 Project Description

The **Interactive Personal Data Collector** is a beginner-friendly Python program that collects basic personal information from the user.

The program asks the user to enter their:

* Name
* Age
* Height
* Favourite number

It then displays the entered information along with the **data type** of each value. Finally, it calculates the user's approximate birth year.

## 🔗 Run the Program Online

You can run the program directly using **OnlineGDB**:

👉 https://onlinegdb.com/L03u7e9qk

## ✨ Features

* 👤 Takes the user's name as input
* 🎂 Takes the user's age as an integer
* 📏 Takes the user's height as a floating-point number
* 🔢 Takes the favourite number as an integer
* 🔍 Displays the data type using `type()`
* 🧮 Calculates the approximate birth year

## 🛠️ Technologies Used

* **Python 3**
* `input()`
* `print()`
* `int()`
* `float()`
* `type()`

## 💻 Source Code

```python
print("Welcome to the Interactive Personal Data Collecter!")

name = input("Please enter your name :- ")

age = int(input("Please enter your age :- "))

height = float(input("Please enter your height :- "))

favnumber = int(input("Please enter your favourite number :- "))


print("Name:", name)
print("Type:", type(name))

print("Age:", age)
print("Type:", type(age))

print("Height:", height)
print("Type:", type(height))

print("Favourite Number:", favnumber)
print("Type:", type(favnumber))

birthyear = 2026 - age

print("Your birth is approximately:", birthyear)
```

## 📚 Python Concepts Used

### 1. `input()`

The `input()` function is used to take information from the user.

```python
name = input("Please enter your name :- ")
```

### 2. `int()`

The `int()` function converts user input into an integer.

```python
age = int(input("Please enter your age :- "))
```

It is used for the user's age and favourite number.

### 3. `float()`

The `float()` function converts the input into a decimal number.

```python
height = float(input("Please enter your height :- "))
```

### 4. `type()`

The `type()` function displays the data type of a variable.

```python
print(type(name))
```

For example:

* Name → `str`
* Age → `int`
* Height → `float`
* Favourite Number → `int`

### 5. Arithmetic Operation

The program calculates the approximate birth year using subtraction:

```python
birthyear = 2026 - age
```

## 🖥️ Example Output

```text
Welcome to the Interactive Personal Data Collecter!

Please enter your name :- Grishma
Please enter your age :- 20
Please enter your height :- 1.65
Please enter your favourite number :- 7

Name: Grishma
Type: <class 'str'>

Age: 20
Type: <class 'int'>

Height: 1.65
Type: <class 'float'>

Favourite Number: 7
Type: <class 'int'>

Your birth is approximately: 2006
```

## 🎯 Learning Objectives

This project helps beginners understand:

* Variables
* Python data types
* User input
* Type conversion
* String data
* Integer data
* Float data
* `type()` function
* Basic arithmetic operations
* Output using `print()`

## 📂 Project Structure

```text
Interactive-Personal-Data-Collector/
│
├── personal_data_collector.py
└── README.md
```

## 👩‍💻 Author

**Grishma Maniya**

---

⭐ **Beginner Python Project — Interactive Personal Data Collector**
live project link:
https://onlinegdb.com/L03u7e9qk

output screenshots:<img width="501" height="257" alt="image" src="https://github.com/user-attachments/assets/120b92a1-b980-40e3-b244-c7a995968cd7" />


