## Programming Assignment_2
-------------

### 1. Write a Python program to convert kilometers to miles?
##### Sol.


```python
km = 6

miles = km/1.60934

print("For {}km equivalent distance in miles = {}".format(km, miles))
```

    For 6km equivalent distance in miles = 3.7282364198988405
    

### 2.Write a Python program to convert Celsius to Fahrenheit?
##### Sol.


```python
c = 35

f = (9*c/5)+32

print("For Celsius = {} equivalent Fahrenheit = {}".format(c, f))
```

    For Celsius = 35 equivalent Fahrenheit = 95.0
    

### 3. Write a Python program to display calendar?
##### Sol.


```python
import calendar
```


```python
year = 2021
month = 12

print(calendar.month(year, month))
```

       December 2021
    Mo Tu We Th Fr Sa Su
           1  2  3  4  5
     6  7  8  9 10 11 12
    13 14 15 16 17 18 19
    20 21 22 23 24 25 26
    27 28 29 30 31
    
    


```python
year = 2022

print(calendar.calendar(year))
```

                                      2022
    
          January                   February                   March
    Mo Tu We Th Fr Sa Su      Mo Tu We Th Fr Sa Su      Mo Tu We Th Fr Sa Su
                    1  2          1  2  3  4  5  6          1  2  3  4  5  6
     3  4  5  6  7  8  9       7  8  9 10 11 12 13       7  8  9 10 11 12 13
    10 11 12 13 14 15 16      14 15 16 17 18 19 20      14 15 16 17 18 19 20
    17 18 19 20 21 22 23      21 22 23 24 25 26 27      21 22 23 24 25 26 27
    24 25 26 27 28 29 30      28                        28 29 30 31
    31
    
           April                      May                       June
    Mo Tu We Th Fr Sa Su      Mo Tu We Th Fr Sa Su      Mo Tu We Th Fr Sa Su
                 1  2  3                         1             1  2  3  4  5
     4  5  6  7  8  9 10       2  3  4  5  6  7  8       6  7  8  9 10 11 12
    11 12 13 14 15 16 17       9 10 11 12 13 14 15      13 14 15 16 17 18 19
    18 19 20 21 22 23 24      16 17 18 19 20 21 22      20 21 22 23 24 25 26
    25 26 27 28 29 30         23 24 25 26 27 28 29      27 28 29 30
                              30 31
    
            July                     August                  September
    Mo Tu We Th Fr Sa Su      Mo Tu We Th Fr Sa Su      Mo Tu We Th Fr Sa Su
                 1  2  3       1  2  3  4  5  6  7                1  2  3  4
     4  5  6  7  8  9 10       8  9 10 11 12 13 14       5  6  7  8  9 10 11
    11 12 13 14 15 16 17      15 16 17 18 19 20 21      12 13 14 15 16 17 18
    18 19 20 21 22 23 24      22 23 24 25 26 27 28      19 20 21 22 23 24 25
    25 26 27 28 29 30 31      29 30 31                  26 27 28 29 30
    
          October                   November                  December
    Mo Tu We Th Fr Sa Su      Mo Tu We Th Fr Sa Su      Mo Tu We Th Fr Sa Su
                    1  2          1  2  3  4  5  6                1  2  3  4
     3  4  5  6  7  8  9       7  8  9 10 11 12 13       5  6  7  8  9 10 11
    10 11 12 13 14 15 16      14 15 16 17 18 19 20      12 13 14 15 16 17 18
    17 18 19 20 21 22 23      21 22 23 24 25 26 27      19 20 21 22 23 24 25
    24 25 26 27 28 29 30      28 29 30                  26 27 28 29 30 31
    31
    
    

### 4. Write a Python program to solve quadratic equation?
##### Sol.


```python

import math

print("ax^2 + bx^1 + c = 0")
print("Enter the coeff a, b and constant c")

a = int(input(("Enter the coeff a: ")))
b = int(input(("Enter the coeff b: ")))
c = int(input(("Enter the constant c: ")))

d = (b**2) - (4*a*c)

root1 = ((-1*b)+(math.sqrt(d))) / (2*a)
root2 = ((-1*b)-(math.sqrt(d))) / (2*a)

print('\nFor quad eq. {}x^2 + ({})x^1 + {}'.format(a,b,c))
print('The solutions are: {} and {}'.format(root1, root2))
```

    ax^2 + bx^1 + c = 0
    Enter the coeff a, b and constant c
    Enter the coeff a: 1
    Enter the coeff b: -9
    Enter the constant c: 14
    
    For quad eq. 1x^2 + (-9)x^1 + 14
    The solutions are: 7.0 and 2.0
    

### 5. Write a Python program to swap two variables without temp variable?
##### Sol.


```python
var1 = 6
var2 = 4

print('Before swap:\nvar1 = {} and var2 = {}'.format(var1, var2))
var2 = var1 + var2
var1 = var2 - var1
var2 = var2 - var1

print('\nAfter swap:\nvar1 = {} and var2 = {}'.format(var1, var2))
```

    Before swap:
    var1 = 6 and var2 = 4
    
    After swap:
    var1 = 4 and var2 = 6
    


```python

```
