# Functions in Python: Modulo Calculator

## 🎯 Aim
Write a python program to define a function named "result" that accepts 2 values and return its sum, subtraction and multiplication.


## 🧠 Algorithm
Start

Input two numbers

Read a

Read b

Call the function result(a, b)

Inside the function:
3.1. Calculate sum = a + b
3.2. Calculate sub = a - b
3.3. Calculate mul = a * b
3.4. Return sum, sub, mul

Receive returned values

Assign sum, sub, mul = result(a, b)

Display the results

Print "Sum is <sum>, Sub is <sub>, & Multiply is <mul>"

Stop

## 🧾 Program

``````````````````````````````````````
def result(a,b):
    sum=a+b
    sub=a-b
    mul=a*b
    return sum,sub,mul
a=int(input())
b=int(input())
sum,sub,mul=result(a,b)
print(f"Sum is {sum},Sub is {sub},&Multiply is {mul}")
``````````````````````````````````````
## Output

<img width="944" height="201" alt="image" src="https://github.com/user-attachments/assets/77fc963e-6bdd-4738-8123-5f5f59b0878c" />


## Result
Therefore to Write a python program to define a function named "result" that accepts 2 values and return its sum, subtraction and multiplication
is compiled nd the output is verified successfully.

