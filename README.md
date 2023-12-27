# Find the GCD of two numbers

## AIM:
To write a program to find the GCD of two numbers using function.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Get the two numbers from the user.
3. Compare the two values, to find the smaller number.
4. Use for() and if() loop to find the GCD of the two numbers.

## Program:
```
/*
Program to find the gcd of two number using function.
Developed by: VIGNESH M
RegisterNumber:  23014020
*/
```python
def gcd():
    a=int(input())
    b=int(input())
    while b!=0:
        a,b=b,a%b
    print("GCD of two numbers is:",a)

## Output:
![image](https://github.com/vigneshvickyu/GCD-of-two-numbers/assets/151948835/094b83e5-5b65-4c7b-ac91-b2070f2a0f08)




## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
