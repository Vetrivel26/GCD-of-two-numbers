# Find the GCD of two numbers

## AIM:
To write a program to find the GCD of two numbers using function.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Get the two numbers from the user.
3. Use if else to find the GCD of the two numbers.
4. print the output

## Program:
```
/*
Program to find the gcd of two number using function.
Developed by: VETRIVEL S
RegisterNumber: 21000733
*/
```
~~~
def gcd_recursive(x,y):
    rem = x%y
    if (rem == 0):
        return y
    else:
        return gcd_recursive(y,rem)
def gcd():
    n,m=int(input()),int(input())
    print("GCD of two numbers is:",gcd_recursive(n,m))
~~~

## Output:
![gcd of two number](gcd.jpg)


## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
