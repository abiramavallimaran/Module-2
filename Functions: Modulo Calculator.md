# Functions in Python: Modulo Calculator

## 🎯 Aim
To write a Python program that defines a function which accepts two values and returns their **modulo** using the `%` operator.

## 🧠 Algorithm
1. Define a function called `result` that takes two arguments `a` and `b`.
2. Inside the function, compute the modulo using `a % b`.
3. Print the result of the modulo operation.
4. Get two integer inputs from the user.
5. Call the `result` function with the user-provided values.

## 🧾 Program
```
def result(a, b):
    mod = a % b
    print("Modulo is:", mod)

num1 = int(input("Enter the first integer: "))
num2 = int(input("Enter the second integer: "))

result(num1, num2)

## Output
Enter the first integer: 15
Enter the second integer: 4
Modulo is: 3
```
## Result
Hence the the modulo is known for the given two numbers.
