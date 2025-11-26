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
```PYTHON
# Open the file story.txt in read mode
file = open("story.txt", "r")

# Initialize counter
count = 0

# Iterate through each line
for line in file:
    # Check if the first character is NOT 'T'
    if not line.startswith('T'):
        count += 1

# Close the file
file.close()

# Print the count
print("Number of lines not starting with 'T':", count)

```
## Output
<img width="438" height="55" alt="Screenshot 2025-11-26 201812" src="https://github.com/user-attachments/assets/d0c39db0-cbfd-49cc-9d0c-23850fb1f615" />

## Result
THUS THE PROGRAM WAS EXECUTED SUCCESSFULLY .
