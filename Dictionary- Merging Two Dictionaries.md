## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program
```
keys = eval(input())
values = eval(input())

result = dict(zip(keys, values))

print(result)
```
## Output
<img width="1135" height="243" alt="image" src="https://github.com/user-attachments/assets/caef2a4d-fa09-4894-8131-7485f2eaec82" />

## Result
Thus the program that merges two dictionaries and combines their key-value pairs is executed successfully.
