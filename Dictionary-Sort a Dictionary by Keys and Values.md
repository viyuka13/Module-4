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
      dictionary = {'apple': 3, 'banana': 1, 'cherry': 2}
      
      sorted_by_keys = dict(sorted(dictionary.items()))
      sorted_by_values = dict(sorted(dictionary.items(), key=lambda item: item[1]))
      
      print("Original dictionary:", dictionary)
      print("Sorted by keys:", sorted_by_keys)
      print("Sorted by values:", sorted_by_values)
## Sample Output
![image](https://github.com/user-attachments/assets/fcd11f94-1187-4dd4-bc0a-1c437d77dca1)

## Result
The Python program to sort a dictionary by keys and values has been executed successfully, and the output has been verified.

