## Sridhar (25017646)


# List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program
```py
l=[1,2,3,4,5,6,7,8]
print(sum(l))
```



## Output
 <img width="1330" height="127" alt="image" src="https://github.com/user-attachments/assets/7fa9c555-42ce-4272-8a99-76eef4830898" />


## Result
successfully wrote Python program that calculates the **sum of all elements** in a list.


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
```py
import re
l=[]
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
for i  in items:
    if not re.search("e",i):
        l.append(i)
print(l)
    
```
## Output
<img width="1197" height="248" alt="image" src="https://github.com/user-attachments/assets/d5230a81-a3bf-47b4-b464-dd3dbf592b16" />


## Result
successfully wrote Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)**.


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
```py
def remove(s):
    n=int(input())
    k=""
    for i in range(len(s)):
        if i!=n:
            k+=s[i]
    return k
print(remove(input()))
```

## Output
<img width="1207" height="232" alt="image" src="https://github.com/user-attachments/assets/df0705b5-d642-449e-9fc5-1b33dd3014da" />

## Result
successfully wrote Python program that accepts a string and removes the character at a specified index.


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
```py
a=input()
b=a[::-1]
if a==b:
    print("this is palindrome")
else:
    print('not palindrome')
```

## Output
<img width="1443" height="208" alt="image" src="https://github.com/user-attachments/assets/b8eef04c-e8b9-4bc2-aa9f-6d8c806f04a7" />

<img width="1290" height="222" alt="image" src="https://github.com/user-attachments/assets/aca24b48-45f4-489d-af43-39dbd300a7aa" />

## Result
successfully wrote Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

# Tuple in Python: Check Element Existence

## 🎯 Aim
To write a Python program that checks if the element `'n'` and the element `8` exist within a given tuple.

## 🧠 Algorithm
1. Define a tuple `x` with some letters and numbers.
2. Use the `in` operator to check if the string `'n'` exists within the tuple.
3. Use the `in` operator to check if the integer `8` exists within the tuple.
4. Print the results.

## 🧾 Program
```py
a=("a","b","c","n",6,7,8)
print("n" in a)
print(8 in a)
print(9 in a)
```

## Output
<img width="1267" height="182" alt="image" src="https://github.com/user-attachments/assets/aeef7332-fb87-4be3-b07d-5ac8c24d3169" />

## Result
successfully wrote Python program that checks if the element `'n'` and the element `8` exist within a given tuple.
