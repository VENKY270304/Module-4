**Exp.No:19  
CLASS AND OBJECTS - AREA OF CIRCLE**

**AIM**

To write a Python program to take the radius from the user and find the area of a circle using the class name pen and function name umbrella.


**ALGORITHM**

1. Begin the program.  
2. Create a class named pen.  
3. Define a method stationary(self, radius) inside the class pen that accepts a radius radius as an argument.  
4. Inside the stationary method:  
   - Calculate the area of a circle using the formula:  
     \[ \text{Area} = \pi \times r^2 \]  
   - Use the math.pi constant to get the value of π and perform the calculation.  
   - Print the result, formatted to two decimal places.  
5. Prompt the user for an integer input to represent the radius of the circle.  
6. Create an instance of the stationary class and store it in the variable p.  
7. Call the pen method of the stationary class, passing the user-provided radius radius as an argument.  
8. Terminate the program.



**PROGRAM**

**212222040177 - Venkatesan M**

import math

class pen:
    def stationary(self, radius):
        area = math.pi * radius * radius
        print(f"Area of circle: {area:.2f}")

radius = float(input())
p = pen()
p.stationary(radius)


**OUTPUT**

![image](https://github.com/user-attachments/assets/0046a2aa-6d10-4621-8e1a-0bc0d6d631f1)


**RESULT**

Thus the program to take the radius from the user and find the area of a circle has been implemented and executed successfully.



