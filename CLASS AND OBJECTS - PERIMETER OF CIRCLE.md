

## CLASS AND OBJECTS - PERIMETER OF CIRCLE

### AIM  

To write a Python program to find perimeter of a circle using class and function.

### ALGORITHM

1. Begin the program.  
2. Define a class circle with a method peri(num) to calculate the perimeter.
   Use the formula: 2 * π * radius.
   Print the perimeter rounded to two decimal places.
3. Input the radius of the circle.
4. Create an object of the class circle.
5. Call the peri() method using the object and pass the radius as an argument.  
6. Terminate the program.

### PROGRAM

```

import math
class circle:
    def peri(num):
        a=2*math.pi*num
        print(f"Perimeter of circle:",round(a,2))
r=int(input())
obj=circle
obj.peri(r)

```

### OUTPUT

![image](https://github.com/user-attachments/assets/e8969f6f-abd1-4612-a9d9-b6b23cd70481)

### RESULT

Thus the Python program to find perimeter of a circle using class and function was successfully created.
