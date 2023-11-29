# Find the square root of a number

## AIM:
To write a program to find the square root of a number.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Assign number_iters = 100 in the function to perform 100 iteratios.
3. Set i = 0.
4. Calculate  number = 0.5 * (number + a / number) for 100 iterations.
5. Return number

## Program:
```
Developed by: vignesh raaj s
RegisterNumber: 23005346
def newton(num,num_iters=100):
    a=float(num)
    for i in range(num_iters):
        num=0.5*(num+a/num)
    return num
a=int(input())
print("Square root of the number:",newton(a))

```

## Output:
![Screenshot 2023-11-29 220344](https://github.com/vigneshraaj00/Square-root-of-a-number/assets/138849113/981a59b2-e810-4959-8251-f51b713c5492)


## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
