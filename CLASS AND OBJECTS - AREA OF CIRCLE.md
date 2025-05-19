# Exp.No:19  
## CLASS AND OBJECTS - AREA OF CIRCLE

---

### AIM  
To write a Python program to take the radius from the user and find the area of a circle using the class name `pen` and function name `math`.

---

### ALGORITHM

1. Begin the program.  
2. Create a class named `pen`.  
3. Define a method `math(self, r)` inside the class `pen` that accepts a radius `r` as an argument.  
4. Inside the `rain` method:  
   - Calculate the area of a circle using the formula:  
     \[ \text{Area} = \pi \times r^2 \]  
   - Use the `math.pi` constant to get the value of π and perform the calculation.  
   - Print the result, formatted to two decimal places.  
5. Prompt the user for an integer input to represent the radius of the circle.  
6. Create an instance of the `pen` class and store it in the variable `u`.  
7. Call the `math` method of the `pen` class, passing the user-provided radius `r` as an argument.  
8. Terminate the program.

---

### PROGRAM

```
import math
class pen:
    def stationary(r):
        return math.pi*r*r
r=int(input())
obj=pen
print("Area of circle:",round(obj.stationary(r),2))
```

### OUTPUT
![image](https://github.com/user-attachments/assets/a9260d0b-4d4e-43bc-8536-69ac5e47aa7e)

### RESULT
Thus,a Python program to take the radius from the user and find the area of a circle using the class name `pen` and function name `math` are verified.


