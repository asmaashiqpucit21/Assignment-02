# Assignment 02: -

### 1. Declare and print a variable with the name "name" containing your name.


```python
name = "Asma"
print(name)
```

    Asma
    

### 2. Create two variables, x and y, and swap their values without using a third variable.


```python
x=10
y=20
x,y=y,x
print("x:",x)
print("y:",y)
```

    20
    10
    

### 3. Calculate the area of a rectangle with length and width stored in variables.¶


```python
length = 5  
width = 10   
area = length * width
print("The area of the rectangle is:", area)
```

    50
    

### 4. Create a variable with a long string (multi-line) and print its length.



```python
A = """My first assignment of neural networks and artificial intelligence"""
print(A)
len(A)
```

    My first assignment of neural networks and artificial intelligence
    66



### 5. Create a variable to store your favorite number and print it.


```python
num = 10
print(num)
```

    10
    

### 6. Declare and assign values to multiple variables to represent the sides of a triangle. Calculate and print its perimeter.


```python
a = 5  
b = 10  
c = 2  
perimeter = a + b + c
print("The perimeter of the triangle is:", perimeter)
```

    17
    

### 7. Store the price of an item in one variable and the quantity in another. Calculate and print the total cost.


```python
price_per_item = 10.0  
quantity = 5  
total_cost = price_per_item * quantity
print("The total cost is:", total_cost)
```

    50
    

### 8. Declare a constant variable for the value of pi (π) and use it to calculate the circumference of a circle with a given radius.


```python
import math
PI = math.pi
radius = 10  
#Circumference = 2 * π * radius
circumference = 2 * PI * radius
print("The circumference of the circle with a radius of", radius, "is:", circumference)
```

    62.857142858
    

### 9. Calculate the sum of two numbers, a and b.


```python
a = 10  
b = 7  
Sum = a + b
print("The sum of", a, "and", b, "is:", Sum)
```

    17
    

### 10. Calculate the product of two numbers, a and b.


```python
a = 5  
b = 7  
P = a * b
print("The product of", a, "and", b, "is:", P)
```

    35
    

### 11. Calculate the result of dividing a by b (with proper error handling for division by zero).


```python
a = 5  
b = 0   
Div = a / b
print("The result of", a, "divided by", b, "is:", Div)

```


    ---------------------------------------------------------------------------

    ZeroDivisionError                         Traceback (most recent call last)

    Cell In[13], line 3
          1 a = 5
          2 b = 0
    ----> 3 div = a/b
          4 print(div)
    

    ZeroDivisionError: division by zero


### 12. Calculate the square of a number x.


```python
x = 5  
square = x ** 2
print("The square of", x, "is:", square)
```

    25
    

### 13. Calculate the remainder when a is divided by b.


```python
a = 17  
b = 5   
remainder = a % b
print("The remainder when", a, "is divided by", b, "is:", remainder)
```

    2
    

### 14. Calculate the result of dividing 17 by 3 and print the quotient and remainder.


```python
x=18
y=3
quotient = x//y
remain = x%y
```


```python
print(quotient)
```

    6
    


```python
print(remain)
```

    0
    

### 15. Calculate the area of a square with a given side length.


```python
length = 4
area = length * length
print(area)
```

    16
    

### 16. Calculate the average of five numbers.


```python
number1 = 10  
number2 = 15  
number3 = 20  
number4 = 25  
number5 = 30  
total = number1 + number2 + number3 + number4 + number5
average = total / 5
print("The average of the five numbers is:", average)
```

### 17. Create a variable with a boolean value and print its opposite value.


```python
my_boolean = True
opposite_value = not my_boolean
print(opposite_value)
```

    False
    

### 18. Store your birth year in a variable and calculate your age.



```python
birth_year = 2000
current_year = 2023
age = current_year - birth_year
print(age)
```

    23
    

### 19. Create a variable with an integer and convert it to a float.


```python
var = 42
my_float = float(var)
print(my_float)
```


### 20. Create a variable with a float and convert it to an integer.


```python
my_float = 3.14159
my_integer = int(my_float)
print(my_integer)
```


    3


### 21. Create a variable with a string that represents an integer and convert it to an integer.


```python
my_string = "123"
my_integer = int(my_string)
print(my_integer)
```



    123



### 22. Create a variable with a string that represents a float and convert it to a float.


```python
my_string = "3.14159"
my_float = float(my_string)
print(my_float)
```



    3.14159



### 23. Create a variable with a number and convert it to a string.


```python
number = 42
String = str(number)
print(String)
```




    42





### 24. Calculate the absolute value of a number.


```python
n = -5
absolute_value = abs(n)
print(absolute_value)
```

    5
    

### 25. Calculate the square root of a number.


```python
import math
num = 25
square_root = math.sqrt(num)
print(square_root)
```

    5.0
    

### 26. Calculate the value of a raised to the power of b.


```python
a = 2
b = 3
result = a ** b
print(result)
```

    8
    

### 27. Round a float to the nearest integer.


```python
my_float = 3.8
rounded_integer = round(my_float)
print(rounded_integer)
```

    4
    

### 28. Combine multiple conditions using logical operators and print the result.


```python
p = 2
q = 5
con1 = p>1
con2 = q>4
res = con1 and con2
print(res)
```


    True


### 2nd condition


```python
p = 2
q = 5
con1 = p<1
con2 = q>4
res = con1 or con2
print(res)
```

    True
    

### 3rd condition


```python
p = 2
q = 5
con1 = p>1
con2 = q<4
res = not con1
print(res)
```

    False
    


### 29. Generate a random number between 1 and 100.


```python
import random
RN = random.randint(1, 100)
print(RN)

```

    5
    


```python

```
