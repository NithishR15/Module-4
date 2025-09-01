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
a=eval(input())
b=eval(input())
c=a.copy()
c.update(b)
print(c)
```

## Output
<img width="1204" height="364" alt="image" src="https://github.com/user-attachments/assets/8e1f86c5-cfec-4c6e-959f-4bb9ac94cd34" />
<img width="1193" height="366" alt="image" src="https://github.com/user-attachments/assets/bebc6957-b15c-4286-ac31-353d1ea5e762" />

## Result
Thus the program executed successfully.
