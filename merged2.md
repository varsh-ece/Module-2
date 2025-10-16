# Built-in Functions -Binary Conversion Using Built-in Functions in Python

## 🎯 Aim
To write a Python program to convert the given number into its **binary representation** using built-in Python functions.

## 🧠 Algorithm
1. declare a variable a ,and get the input from user.
2. Use the built-in `bin()` function to convert the number to binary.
3. Print the result.

## 🧾 Program

`````````````````
a=int(input()
print(bin(a))
``````````````````


## Output
<img width="860" height="260" alt="image" src="https://github.com/user-attachments/assets/7aaea421-bb19-4199-80bf-59c6da96186d" />


## Result
Therefore to write a Python program to convert the given number into its **binary representation** using built-in Python functions is
compiled and the output is verified successfully.

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

# Lambda Function in Python: Addition of Two Numbers

## 🎯 Aim
Write a function which takes two arguments: a and b and returns the multiplication of them: a*b. Assign it to a variable named: f. using python
## 🧠 Algorithm
Start

Input two numbers

Read i

Read j

Define a lambda function

f = lambda a, b : a * b
(This function takes two arguments a and b and returns their product.)

Call the lambda function with inputs

Compute f(i, j)

Store the result (product)

Display the result

Print the product of i and j

Stop
## 🧾 Program
`````````````````````````````
i=int(input())
j=int(input())

f = lambda a, b: a*b

print(f(i, j))
`````````````````````````````````````

## Output
<img width="570" height="230" alt="image" src="https://github.com/user-attachments/assets/a3010e71-acc6-41db-83a0-030e5682e1e7" />


## Result
therefore to Write a function which takes two arguments: a and b and returns the multiplication of them: a*b. Assign it to a variable named: f. using python
is compiled and the output is verified successfully.

# 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.

---

## 🎯 Aim

To write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.

---

## 🧠 Algorithm

1. Start the program.
2. Input the number of rows from the user.
3. Loop from 0 to the number of rows.
4. For each row:
   - Print appropriate spaces to shape the triangle.
   - Compute values using the formula:  
     \[
     C(n, k) = \frac{n!}{k!(n-k)!}
     \]
5. Print all rows of Pascal’s Triangle.
6. End the program.

---

## 🧪 Program
```
rows = int(input())
coef = 1

for i in range(1, rows+1):
    for space in range(1, rows-i+1):
        print(" ",end="")
    for j in range(0, i):
        if j==0 or i==0:
            coef = 1
        else:
            coef = coef * (i - j)//j
        print(coef, end = " ")
    print()
```
## Sample Output
![image](https://github.com/user-attachments/assets/f852768f-ddf9-4977-8f28-11abd2af690a)

## Result
Thus,the Python program that generates Pascal's Triangle using numbers. The number of rows is accepted from the user is created successfully.


## Loops in Python: Palindrome Number Checker

## 🎯 Aim
To write a Python program that checks whether a given number is a **palindrome** using loops.

## 🧠 Algorithm
1. Get input from the user and assign it to a variable `num`.
2. Assign the value of `num` to a temporary variable `temp`.
3. Initialize a variable `rev` to 0 (used to store the reversed number).
4. Use a `while` loop to reverse the digits:
   - While `temp > 0`:
     - `rev = (10 * rev) + temp % 10`
     - `temp = temp // 10`
5. After the loop, compare `rev` with `num`:
   - If equal, print that the number is a palindrome.
   - Else, print that it is not a palindrome.

## 🧾 Program
```
num=int(input())
rev=0
temp=num
while temp>0:
    rev=(10*rev)+temp%10
    temp//=10
if rev==num:
    print("The given number {} is a Palindrome".format(num))
else:
    print("The given number {} is not a palindrome".format(num))
```
## Output
![image](https://github.com/user-attachments/assets/f5719231-1cc7-443a-9942-d40ff7ec1748)

## Result
Thus,the Python program that checks whether a given number is a palindrome using loops is created successfully.
