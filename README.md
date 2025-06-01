# NAME : VIKASKUMAR M
# REG NO: 212224220122
# 1-Built-in Functions -Binary Conversion Using Built-in Functions in Python

## 🎯 Aim
To write a Python program to convert the number **16** into its **binary representation** using built-in Python functions.

## 🧠 Algorithm
1. Assign the value `16` to a variable `a`.
2. Use the built-in `bin()` function to convert the number to binary.
3. Print the result.

## 🧾 Program
```
a=16 
print(bin(a)
```

## Output

![image](https://github.com/user-attachments/assets/f6b7d2e7-6d89-4be0-bee5-163d9413e74c)

## Result
Thus ,the program is executed successfully.

# 2-Functions in Python: Modulo Calculator

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
mod=a%b 
print(f"modulo is {mod}") 
a = int(input()) 
b = int(input())
```

## Output

![image](https://github.com/user-attachments/assets/be96e365-5eb7-4912-9890-02fbb4b6a41b)

## Result
Thus ,the program is executed successfully.

# 3-Lambda Function in Python: Addition of Two Numbers

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
f=lambda a,b:a+b
print(f(a,b))
```
## Output

![image](https://github.com/user-attachments/assets/a64fd256-6f1a-49ac-b53d-695bf4362782)

## Result
Thus ,the program is executed successfully.

# 4-🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

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
def triangle(n):
    for i in range(n):
        num=1
        row=[]
        for j in range(i+1):
            row.append(num)
            num=num*(i-j)//(j+1)
        print(*row)
n=int(input())
triangle(n)
```

## Sample Output

![image](https://github.com/user-attachments/assets/a1f10fe1-ac6b-49ad-830e-292cc33be7c5)

## Result

Thus ,the program is executed successfully.

## 5-Loops in Python: Palindrome Number Checker

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

![image](https://github.com/user-attachments/assets/807f45db-39d4-4b5e-ae24-04ebb7cf3e64)

## Result
Thus ,the program is executed successfully.
