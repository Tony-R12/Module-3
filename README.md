# List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program
```
items=[1,2,-8]
sum_numbers = sum(items)
print(sum_numbers)
```

## Output
<img width="288" height="155" alt="image" src="https://github.com/user-attachments/assets/93050e69-ce90-4a32-b998-1e9f2d8a2777" />


## Result
Thus,a Python program that calculates the **sum of all elements** in a list is created successfully.

# Regex in Python: Filter Words Without the Letter 'e'

## 🎯 Aim
To write a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)**.

## 🧠 Algorithm
1. Import the `re` module.
2. Initialize an empty list `l1` to store results.
3. Define a list of words:  
   `items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']`
4. Iterate through each word in the list:
   - Use `re.search(r"e", i)` to check if the word contains `'e'`.
   - If **not**, append the word to `l1`.
5. Print the final filtered list.

## 🧾 Program
```
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
filtered_items=[item for item in items if 'e' not in item]
print(filtered_items)
```
## Output
<img width="440" height="159" alt="image" src="https://github.com/user-attachments/assets/1803930a-d2d0-4768-af37-64591356f295" />


## Result
Thus,a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)** is created successfully'


# Module-3
# 🧹 Strings-Remove Nth Index Character from a String

## 🎯 Aim
To write a Python program that accepts a string and removes the character at a specified index.

## 🧠 Algorithm
1. Define a function named `remove` that takes the input string as an argument.
2. Read the index `n` from the user input.
3. Initialize an empty string `a` to store the new string.
4. Iterate over each index of the string using a `for` loop.
5. Check if the current index `i` is not equal to `n`.
6. If `i != n`, append the character at index `i` to string `a`.
7. After the loop, return the modified string `a`.
8. Print the final result.

## 💻 Program
```
def remove(s):
        new=s[:n]+s[n+1:]
        print(new)
n=int(input())
```

## Output
<img width="627" height="206" alt="image" src="https://github.com/user-attachments/assets/bb1ec3ad-4e99-43ef-96e9-b08af450e3fc" />


## Result
Thus, a Python program that accepts a string and removes the character at a specified index is created successfully.


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


# Tuple in Python: Check Element Existence

## 🎯 Aim
To write a Python program that checks if the element `'n'` and the element `8` exist within a given tuple.

## 🧠 Algorithm
1. Define a tuple `x` with some letters and numbers.
2. Use the `in` operator to check if the string `'n'` exists within the tuple.
3. Use the `in` operator to check if the integer `8` exists within the tuple.
4. Print the results.

## 🧾 Program
```
t=eval(input())
print('n' not in t)
print('8' in t)
```

## Output
<img width="783" height="236" alt="image" src="https://github.com/user-attachments/assets/c63e78d7-386a-4885-870f-da5bd5d1c7fa" />


## Result
Thus,a Python program that checks if the element `'n'` and the element `8` exist within a given tuple is created successfully.



