# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

## 🧠 Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

---

## 🧪Program
```
d={'c':3,'a':1,'b':2}
sk=dict(sorted(d.items()))
sv=dict(sorted(d.items(),key=lambda item:item[1]))
print(d)
print(sk)
print(sv)
```
## Sample Output
<img width="367" height="218" alt="image" src="https://github.com/user-attachments/assets/265b94a0-13fb-4a26-b995-27dc2a7972f0" />


## Result

Thus the program to sort a dictionary by keys and values has been executed successfully.
The original and sorted dictionaries are displayed.
