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
```PYTHON
try:
    # Taking 3 elements input from the user
    L = []
    for i in range(3):
        item = ['laptop','mobile','pen']
        L.append(item)

    # Trying to access index 4
    print(L[4])

except IndexError:
    print("check index range")

```
## Output
<img width="957" height="246" alt="438332172-caa1949e-6a6a-4c0e-b152-491520238b0c" src="https://github.com/user-attachments/assets/f8b78f2f-610a-42ff-9fc9-6acab9884049" />

## Result
THUS THE PROGRAM WAS EXECUTED SUCCESSFULLY .
