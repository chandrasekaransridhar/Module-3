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
