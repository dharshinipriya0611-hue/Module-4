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
~~~
dict1={2:56,1:2,5:12,4:24,6:18,3:323}
print("Keys and Values sorted in alphabetical order by the value")
#sort_dict=(sorted(dict1.items()))
print(sorted(dict1.items(),key=lambda kv:(kv[1],kv[0])))
~~~

## Sample Output
<img width="1127" height="155" alt="image" src="https://github.com/user-attachments/assets/d9a046f9-5fdf-4195-98ae-fc61b3c413f2" />


## Result
Thus the output is verified.

