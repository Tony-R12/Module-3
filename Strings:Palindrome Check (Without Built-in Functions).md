# Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

## 🧠 Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program
```
def palindrome(a):
    rev=''.join(reversed(a))
    if a==rev:
        print("The entered string is palindrome")
    else:
        print("The entered string is not palindrome")
string=input()
palindrome(string)
```

## Output
<img width="952" height="213" alt="image" src="https://github.com/user-attachments/assets/80f2c0c7-6ab7-4fe1-bde8-17afa2c1e4d2" />


## Result
Thus,a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions is created successfully.
