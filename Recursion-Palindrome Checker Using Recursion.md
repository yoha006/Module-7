# 🔁 Recursion:Palindrome Checker Using Recursion in Python

## 🎯 AIM:
To write a Python program to check whether a given string is a **palindrome** using **recursion**.

---

## 🧠 ALGORITHM:

1. **Start**
2. Define a recursive function `is_palindrome(word)`
   - **Base Case:** If the string length is less than 1, return `True`
   - **Recursive Case:** If the first and last characters match, call the function recursively on the substring without first and last characters
   - Else, return `False`
3. Get input from the user
4. Call the recursive function
5. Print whether the string is a palindrome
6. **Stop**

---

## 💻 PROGRAM:
ADD CODE HERE
```
def is_palindrome(word): if len(word) <= 1: return True else: return word

str=input() if str==str[::-1]: print("String is a palindrome") else: print("String is not a palindrome")
```
## OUTPUT
![image](https://github.com/user-attachments/assets/4deec7d2-bd39-4ac7-bc7a-9dadd83593e1)

## RESULT
Thus, the program has been execueted successfully.
