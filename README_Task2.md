# Personalized Greeting Program in Python

##  Overview

This Python program takes a user's **first name** and **last name** as input, combines them to form a **full name**, and then displays a **personalized greeting message**. It demonstrates basic concepts such as string input, string concatenation, and formatted output.

---

##  Functionalities

### 1. User Input

* The program prompts the user to enter their **first name** and **last name** using the `input()` function.
* The input values are stored as **string variables**.

```python
name_1 = input("Enter your first name : ")
name_2 = input("Enter your last name : ")
```

---

### 2. String Concatenation

* The first name and last name are combined using the `+` operator.
* A space (`" "`) is added between them to form a properly formatted full name.

```python
full_name = name_1 + " " + name_2
```

---

### 3. Output Display

* The program displays a greeting message using the `print()` function.
* The full name is included in the message to make it personalized.

```python
print("Hello," + full_name + "! Welcome to the Python programme.")
```

---

##  Program Workflow

1. Ask the user to enter their first name
2. Ask the user to enter their last name
3. Combine both inputs into a full name
4. Display a personalized welcome message

---

##  Example Output

```
Enter your first name : Nabanita
Enter your last name : Barai
Hello, Nabanita Barai! Welcome to the Python programme.
```
