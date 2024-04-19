# Python_Week_2

## Function
A python program is made of many lines of code, stored in a file with a name like "example.py". It's natural to have a way to divide the lines code up into sensible sub-parts, and these are called functions. Almost all the code you work with in Python is inside a function.
- A function is a block of code which only runs when it is called.
- You can pass data, known as parameters, into a function.
- In Python a function is defined using the "def" keyword
- A function can return data as a result.

![Screenshot (770)](https://github.com/Rnovranza/Python_Week_2/assets/134476980/dcebdd3c-06b2-49dd-bb13-6db0d6bc3dc1)

### Return
The Python return statement is a special statement inside a function or method to send the function’s result back to the caller. 
- A return statement consists of the return keyword followed by an optional return value.
- functions can return numeric values (int, float, and complex values), collections and sequences of objects (list, tuple, dictionary, or set objects), user-defined objects, classes, functions, and even modules or packages.

![Screenshot (772)](https://github.com/Rnovranza/Python_Week_2/assets/134476980/b01fd54d-adc1-491c-a001-8ecfe0464091)

A function's output can be saved in a variable, setting it apart from a void function that doesn't produce any output. This distinctive characteristic determines if a value is provided by the function.

![Screenshot (775)](https://github.com/Rnovranza/Python_Week_2/assets/134476980/5cd1747d-cd1e-4b2d-9f4c-7b365f28012d)

### Pass by reference vs value
- all parameters (arguments) in python are pass by reference vs value meaning that when we change a var then the data that refers to it will also change, both within the function and outside the function.
- except when performing assignment operations that will change the parameter reference

#### - Pass by value
The value of the variable is copied and passed to the function. Changes to parameters inside the function do not affect the original variables outside the function.

![Screenshot (777)](https://github.com/Rnovranza/Python_Week_2/assets/134476980/ae1c3ab3-7653-47ff-b063-0486b7b6ffdc)
In the above example, although the value of r is changed inside the function, the value of radius outside the function remains unchanged.

#### - Pass by reference
The memory address of the variable is passed to the function. Changes to the parameters inside the function will affect the original variables outside the function.

![Screenshot (779)](https://github.com/Rnovranza/Python_Week_2/assets/134476980/cf43493b-a384-44ab-9509-beb97fb47902)
###### 
Since we only appended a value to the list without reassigning the variable, there is no decoupling or recoupling taking place. Both the inner and outer variables still refer to the same object, while the content of that object has been altered by the addition of the new value.

## Numpy
NumPy is a Python library that provides multidimensional array objects, various derived objects (such as masked arrays and matrices), and various routines for fast operations on arrays, including math, logic, shape manipulation, sorting, selection, I/O, discrete Fourier transform, basic linear algebra, basic statistical operations, random simulation, and more.

