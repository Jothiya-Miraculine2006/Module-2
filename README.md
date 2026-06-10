# Built-in Functions -Binary Conversion Using Built-in Functions in Python

## 🎯 Aim
To write a Python program to convert the number **16** into its **binary representation** using built-in Python functions.

## 🧠 Algorithm
1. Assign the value `16` to a variable `a`.
2. Use the built-in `bin()` function to convert the number to binary.
3. Print the result.

## 🧾 Program
```
x=16
y=bin(x)
print(y)
```

## Output
<img width="582" height="409" alt="image" src="https://github.com/user-attachments/assets/be410527-300d-4a3a-93a4-aa3373240caf" />


## Result
Thus, the program to perform Binary Conversion using Built-in Functions in Python was executed successfully.
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
    modulo_value = a % b
    return modulo_value

a=int(input())
b=int(input())
print("modulo is", result(a, b))

```

## Output

<img width="848" height="398" alt="image" src="https://github.com/user-attachments/assets/3c7aca7c-63c8-4993-a2c4-267098b960f3" />


## Result
Thus, the program to implement a Modulo Calculator using Functions in Python was executed successfully.
# Lambda Function in Python: Addition of Two Numbers

## 🎯 Aim
To write a Python program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their sum.

## 🧠 Algorithm
1. Get two integer inputs from the user.
2. Use a **lambda function** to define a function `f` that returns `a + b`.
3. Call the function with the user inputs and print the result.

## 🧾 Program
```
i=int(input())
j=int(input())
z=int(input())

f = lambda a, b,c: a+b+c

print(f(i, j,z))S
```

## Output
<img width="727" height="563" alt="image" src="https://github.com/user-attachments/assets/67a02963-43ac-45fa-afda-36f4d5851505" />

## Result
Thus,the Python program that defines a lambda function which takes two arguments a and b, and returns their sum is created successfully.
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

<img width="726" height="796" alt="image" src="https://github.com/user-attachments/assets/efad68e5-0f34-4ca2-9253-5994a5949e87" />

<img width="731" height="805" alt="image" src="https://github.com/user-attachments/assets/8600b65b-7dca-4d60-8e3f-b52b1bc87ba7" />



## Result

Thus,the Python program that generates Pascal's Triangle using numbers. The number of rows is accepted from the user is created successfully.
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

<img width="726" height="796" alt="image" src="https://github.com/user-attachments/assets/efad68e5-0f34-4ca2-9253-5994a5949e87" />

<img width="731" height="805" alt="image" src="https://github.com/user-attachments/assets/8600b65b-7dca-4d60-8e3f-b52b1bc87ba7" />



## Result

Thus,the Python program that generates Pascal's Triangle using numbers. The number of rows is accepted from the user is created successfully.
