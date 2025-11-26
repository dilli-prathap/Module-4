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

```PYTHON
import math

class cse:
    def mech(self, radius):
        area = math.pi * radius ** 2
        print(f"Area of circle: {area:.2f}")
r = float(input())
obj = cse()
obj.mech(r)

```
## Output
<img width="955" height="240" alt="438326712-732d2ade-138c-4452-af08-c761fa1b92fd" src="https://github.com/user-attachments/assets/0ff805f6-d848-4f6c-844c-8eb2b5d6fca1" />

## Result
THUS THE PROGRAM WAS EXECUTED SUCCESSFULLY .
