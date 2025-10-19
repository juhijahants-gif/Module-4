## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program
Add code here
```
dict1=eval(input())
dict2=eval(input())
dict1.update(dict2)
print(dict1)
```

## Output
![WhatsApp Image 2025-10-19 at 19 53 58_d7894fa8](https://github.com/user-attachments/assets/d603307a-15dd-413f-be8d-3a1edb7e5da6)


## Result
The program successfully merges two dictionaries.
All key-value pairs from both dictionaries are combined.
If a key exists in both dictionaries (like 'b'), the value from the second dictionary (dict2) overwrites the value from the first dictionary (dict1).
