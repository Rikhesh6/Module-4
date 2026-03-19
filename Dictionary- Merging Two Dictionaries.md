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
dict1={'a':1,'b':2}
dict2={'b':3,'c':4}
def merge():
    return{**dict1,**dict2}
print(merge())
```

## Output
<img width="382" height="160" alt="image" src="https://github.com/user-attachments/assets/c8e48190-d960-4442-a136-4642fd05c340" />


## Result
Thus the program to merge two dictionaries using unpacking has been executed successfully.
The values from the second dictionary overwrite duplicates from the first.
