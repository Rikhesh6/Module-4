# Classes and Objects in Python: Calculate the Area of a Circle

## 🎯 Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

## 🧠 Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## 🧾 Program
```
class cse:
    def mech(self,r):
        print(3.14*r*r)
r=float(input())
obj=cse()
obj.mech(r)
```

## Output
<img width="427" height="196" alt="image" src="https://github.com/user-attachments/assets/f573e11e-48e2-4d85-a6c9-8fd94ee9777d" />


## Result
Thus the program to find the area of a circle using class and method has been executed successfully.
The radius is accepted from the user and the area is calculated.

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

# Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program
```
list1=[1,2,3]
try:
    print(list1[5])
except:
    print("You're out of list range")
```

## Output
<img width="382" height="173" alt="image" src="https://github.com/user-attachments/assets/3d893085-ac44-42d8-983f-7f07c6afe797" />


## Result
Thus the program to handle index error using try-except has been executed successfully.
The error is caught and a custom message is displayed.

# File Handling in Python: Count Lines Not Starting with 'T'

## 🎯 Aim
To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

## 🧠 Algorithm
1. Open the file `story.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is **not** `'T'`.
   - If the line does not start with `'T'`, increment the `count` by 1.
4. After processing all lines, print the `count` value, which represents the number of lines that do not start with `'T'`.

## 🧾 Program
```
f=open("story.txt","r")
count=0
for line in f:
    if not line.startswith('T'):
        count+=1
print(count)
```
## Output
<img width="369" height="166" alt="image" src="https://github.com/user-attachments/assets/cba8bd1b-09bf-439c-9fa7-8ad8568a6801" />

## Result
Thus the program to count lines not starting with 'T' has been executed successfully.
The total number of such lines is displayed.

