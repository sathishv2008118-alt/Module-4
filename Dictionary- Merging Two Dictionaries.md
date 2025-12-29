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
dict1=eval(input())
dict2=eval(input())
dict1.update(dict2)
print(dict1)
```
## Output
<img width="819" height="189" alt="530350194-8c29c2f0-913d-4d67-b26c-d968e384d44e" src="https://github.com/user-attachments/assets/898ae838-377d-4f8b-a719-28b281ade3b0" />

## Result
The program successfully merges two dictionaries. All key-value pairs from both dictionaries are combined. If a key exists in both dictionaries (like 'b'), the value from the second dictionary (dict2) overwrites the value from the first dictionary (dict1).
