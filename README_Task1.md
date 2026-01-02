# Basic Mathematical Operations Program

##  Overview

This Python program performs **basic arithmetic operations**—addition, subtraction, multiplication, and division—on two numbers provided by the user. It is a simple console-based program suitable for beginners learning Python input, variables, operators, and output statements.

---

##  Functionalities

### 1. User Input

* The program asks the user to enter **two integer numbers** using the `input()` function.
* The input values are converted into integers using the `int()` function.

```python
num1 = int(input("Enter the first number : "))
num2 = int(input("Enter the second number : "))
```

---

### 2. Arithmetic Operations

The program performs the following arithmetic operations:

####  Addition

* Adds the two numbers using the `+` operator.

```python
addition = num1 + num2
```

####  Subtraction

* Subtracts the second number from the first using the `-` operator.

```python
subtraction = num1 - num2
```

####  Multiplication

* Multiplies the two numbers using the `*` operator.

```python
multiplication = num1 * num2
```

####  Division

* Divides the first number by the second using the `/` operator.
* The result may be a floating-point value.

```python
division = num1 / num2
```

---

### 3. Output Display

* The results of all arithmetic operations are displayed using the `print()` function in a user-friendly format.

```python
print("Addition : ", addition)
print("Subtraction : ", subtraction)
print("Multiplication : ", multiplication)
print("Division : ", division)
```

---

##  Program Workflow

1. Prompt user to enter the first number
2. Prompt user to enter the second number
3. Perform addition, subtraction, multiplication, and division
4. Display the results on the screen

---

##  Example Output

```
Enter the first number : 10
Enter the second number : 5
Addition :  15
Subtraction :  5
Multiplication :  50
Division :  2.0
```
