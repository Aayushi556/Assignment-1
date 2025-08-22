# Assignment-1
# Basic Arithmetic Operations in Python

This is a simple Python program that takes two numbers as input from the user and performs basic arithmetic operations: addition, subtraction, multiplication, and division.

## 📋 Program Explanation
1. The program asks the user to enter two numbers.
2. It calculates:
   - **Sum** (addition)
   - **Difference** (subtraction)
   - **Product** (multiplication)
   - **Quotient** (division)
3. It displays the results on the screen.

## 💻 Code
```python
num1 = int(input("enter the first number: "))
num2 = int(input("enter the second number: "))

sum = num1 + num2
sub = num1 - num2
mul = num1 * num2
div = num1 / num2

print("the sum is", sum)
print("the sub is", sub)
print("the multiplication is", mul)
print("division = ", div)
```
Output
enter the first number: 10
enter the second number: 5
the sum is 15
the sub is 5
the multiplication is 50
division =  2.0


# Full Name Greeting Program

This is a simple Python program that asks the user to enter their first and last name, combines them into a full name, and prints a personalized welcome message.

## 📋 Program Explanation
1. The program takes two inputs from the user:
   - First name
   - Last name
2. It concatenates them into a single string (`full_name`).
3. It prints the full name.
4. It displays a greeting message using the full name.

## 💻 Code
```python
name = input("enter the name: ")
l_name = input("enter the last name: ")

full_name = name + ' ' + l_name

print(full_name)
print("hey " + full_name + " welcome to university.")
```
Output
enter the name: Aayushi
enter the last name: Kadiyan
Aayushi Kadiyan
hey Aayushi Kadiyan welcome to university.
