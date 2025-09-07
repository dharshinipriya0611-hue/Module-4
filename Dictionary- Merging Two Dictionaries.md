## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. print the merged dictionary.

## 🧾 Program
~~~
dict1 = eval(input())
dict2 = eval(input())
dict2.update(dict1)
print(dict2)
~~~

## Output
<img width="1279" height="185" alt="image" src="https://github.com/user-attachments/assets/0d6450fd-e144-4e9a-b6ec-8b867a408012" />


## Result
Thus the output is verified.
