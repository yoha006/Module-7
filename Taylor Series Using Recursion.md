# 📐 Taylor Series Using Recursion in Python

## 🎯 AIM:
To write a Python program to evaluate a **Taylor Series** using **recursion**, where values of `x` and `n` are taken from the user.

## 🧠 ALGORITHM:

1. **Start**
2. Create variables `x` and `n`
3. Get values for `x` and `n` from the user
4. Define a recursive function `series(x, n)`
   - **Base case:** If `n == 0`, return 1
   - **Recursive case:** Return `x**n / n + series(x, n-1)`
5. Print the result
6. **Stop**

## 💻 PROGRAM:

ADD CODE HERE
```
def series(x,n):
    if n==0:
        return 1
    return x**n+series(x,n-1)
x=int(input())
n=int(input())
result=series(x,n)
print(result)
```
## OUTPUT
![image](https://github.com/user-attachments/assets/60065cca-b313-49ba-a7c8-702d7d798e48)

## RESULT
Thus, the program has been execueted successfully.
