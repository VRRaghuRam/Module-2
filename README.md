# Built-in Functions -Binary Conversion Using Built-in Functions in Python

## 🎯 Aim
To write a Python program to convert the number **16** into its **binary representation** using built-in Python functions.

## 🧠 Algorithm
1. Assign the value `16` to a variable `a`.
2. Use the built-in `bin()` function to convert the number to binary.
3. Print the result.

## 🧾 Program

```
a=16
b=bin(a)
print(b)
```
## Output

![438826667-740cd71d-506b-4f8a-a0b7-5fe8554481a1](https://github.com/user-attachments/assets/f4d3c1a4-4679-492d-a486-aa715c8ceacd)

## Result

Thus the program to convert the number **16** into its **binary representation** using built-in Python functions is executed successfully.


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
def result(a,b):
  m=a%b 
  print(f"modulo is {m}")
 
a = int(input()) 
b = int(input())

```

## Output

![439810898-e9dece7f-876b-442d-a868-abe0f7008174](https://github.com/user-attachments/assets/7a28293a-eb66-4c89-8871-07722d3eba37)

## Result

Thus the program that defines a function which accepts two values and returns their **modulo** using the `%` operator is executed successfully.

# Lambda Function in Python: Addition of Two Numbers

## 🎯 Aim
To write a Python program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their sum.

## 🧠 Algorithm
1. Get two integer inputs from the user.
2. Use a **lambda function** to define a function `f` that returns `a + b`.
3. Call the function with the user inputs and print the result.

## 🧾 Program

```
a=int(input())
b=int(input())
f = lambda x,y: z+y
print(f(a,b))
```

## Output

![438836138-3826ebf1-9fe2-439b-b648-94fe609756f9](https://github.com/user-attachments/assets/dd10829f-3d35-4442-82af-da1afaff6cf4)

## Result

Thus the program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their sum is executed successfully.
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
a=int(input())
def fact(x):
    f=1
    for i in range(1,x+1):
        f*=i
    return f
for i in range(a):
    for j in range(i+1):
        a=fact(i)/((fact(j))*fact(i-j))
        print(int(a),end=" ")
    print()
        
```

## Sample Output

![image](https://github.com/user-attachments/assets/5f42a960-dc01-40ec-9ecf-826053e3ff80)

## Result

Thus the program that generates **Pascal's Triangle** using numbers is executed successfully.
