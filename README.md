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

## Pandas


### Data Frame
DataFrame in pandas is a fundamental data structure specifically designed for data analysis and manipulation in Python. It essentially acts as a powerful spreadsheet on steroids but with the added benefits of programming logic and automation. A DataFrame is indeed a collection of Series, where each Series represents a single column of data.

![image](https://github.com/Rnovranza/Python_Week_2/assets/165742717/467ba473-e5a8-4809-8ec6-67c13e3977bd)

It can look at the proportion of the Gender column or count the number of unique values in the "Gender" column of the DataFrame (called df). The result will return a Pandas Series containing the number of occurrences of each unique value, with the value as the index and the number of occurrences as the value in the Series. This gives a good understanding of the distribution of values in the "Gender" column of the DataFrame.

![image](https://github.com/Rnovranza/Python_Week_2/assets/165861920/32ee872d-255e-41f9-b7c1-bc89b47f490e)

Can select specific columns from a DataFrame. The result will be a new DataFrame containing only the selected columns. By using this syntax, it is easier to select a specific subset of DataFrame columns that match the needs of data analysis or processing.

![image](https://github.com/Rnovranza/Python_Week_2/assets/165861920/b6292164-b22d-486a-a3fb-4f7ad1b9ea9f)

![image](https://github.com/Rnovranza/Python_Week_2/assets/165861920/50d04578-19d5-4d89-8f7c-cd30d3fbb7e6)

In Python, when you want to create conditions or criteria in your code, you can use comparison operators and logical operators. Here is a brief explanation of these operators:

1. Comparison Operators:
- `>` (more than): This operator is used to check if the value on the left is greater than the value on the right.
- `<` (less than): This operator is used to check if the value on the left is less than the value on the right.
- `>=` (greater than or equal to): This operator is used to check if the value on the left is greater than or equal to the value on the right.
- `<=` (less than or equal to): This operator is used to check if the value on the left is less than or equal to the value on the right.
- `==` (equal to): This operator is used to check if the value on the left is equal to the value on the right.
- `!=` (not equal to): This operator is used to check if the value on the left is not equal to the value on the right.

2. Logical Operators:
- `and`: This operator returns True if both compared conditions are true.
- `or`: This operator returns True if one or both of the compared conditions are true.
- `not`: This operator is used to reverse the truth value of a condition.

![image](https://github.com/Rnovranza/Python_Week_2/assets/165861920/87212435-b4ec-4459-84a5-7c298c965409)

![image](https://github.com/Rnovranza/Python_Week_2/assets/165861920/a3897cc2-4d5d-4561-8233-c6165b03de1c)

![image](https://github.com/Rnovranza/Python_Week_2/assets/165861920/04536fc9-d980-4ec7-8924-3ff2058ec2ea)

![image](https://github.com/Rnovranza/Python_Week_2/assets/165861920/39d8dfdd-b962-4514-b809-075c445aa793)

![image](https://github.com/Rnovranza/Python_Week_2/assets/165861920/3b52c309-e630-4f72-9365-fb6d25909953)

![image](https://github.com/Rnovranza/Python_Week_2/assets/165861920/93c0d87d-c45c-45b7-905f-5d9c3b3b8b36)

![image](https://github.com/Rnovranza/Python_Week_2/assets/165861920/0f85f7e7-9f46-4f06-b2de-66e7e6774b80)

## Random Library
The random library in Python is a built-in module that provides various functions to perform random operations. It is used to generate random numbers, randomly select items from a list, and randomize the order of elements in a list or array

![image](https://github.com/Rnovranza/Python_Week_2/assets/165861920/106ee879-5fd3-413a-a616-d82cb799cb39)

## Datetime Library
The datetime module can be used to work with dates and times, including
1. Creating random dates and times
2. Creating a Random Time within a Specified Time Range
3. Combining Date and Time

![image](https://github.com/Rnovranza/Python_Week_2/assets/165861920/f25a972d-3965-45c2-9f41-4d61771ea56c)

Then the format can also be changed according to your needs.

![image](https://github.com/Rnovranza/Python_Week_2/assets/165861920/5a082ace-aad6-407d-a035-2689b4e0ded2)

## txt file - open, read, close
Importing text files into Python is a commonly used process in data analysis, text processing, and many other applications. In Python, you can open, read, and close text files using some built-in functions (with a .txt extension).

`Open`
Open a text file using the open() function and need to provide the file name and access mode. The r access mode is used to read the file.

![image](https://github.com/Rnovranza/Python_Week_2/assets/165861920/6ce5e1d7-eb36-437e-b7d2-e5196f792adc)

`Read`
After opening the file, it can read its contents using the read() method or other methods such as readline() to read line by line.

![image](https://github.com/Rnovranza/Python_Week_2/assets/165861920/dcc83741-260c-4e50-8565-75b9b6d50070)

`Close`
After finishing reading or performing other operations on a file, it is important to close it using the close() method.

![image](https://github.com/Rnovranza/Python_Week_2/assets/165861920/26151079-60da-4fe1-9a8d-0f04aee076fe)











