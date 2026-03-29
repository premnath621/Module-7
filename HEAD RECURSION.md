# 🔁 Types of Recursion: Head Recursion in Python

## 🎯 AIM:
To write a Python program to display Arithmetic Progression  series by reading the difference between the numbers and limit  using  head recursion.

## 🧠 ALGORITHM:

1. Start the function fun(n, d).
2. If n is greater than 0, proceed; otherwise, stop.
3. Call fun(n - d, d) to recursively reduce n by d.
4. After the recursive call finishes, print the current value of n on the same line.
5. Read inputs d (step value) and x (starting number).
6. Call fun(x, d) to display numbers from smallest positive step up to x.

## 💻 PROGRAM:
~~~
def fun(n,d):
    if (n > 0):
        fun(n - d,d)
        print(n, end=" ")
 
d= int(input())
x = int(input())
fun(x,d)
