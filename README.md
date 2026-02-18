# -to-calculate-the-roots-of-a-given-quadratic-equation

import math

a = int(input("Enter a: "))
b = int(input("Enter b: "))
c = int(input("Enter c: "))

d = (b * b) - (4 * a * c)

if d >= 0:
    print("Roots are: ")
    x1 = (-b + math.sqrt(d)) / (2 * a)
    x2 = (-b - math.sqrt(d)) / (2 * a)
    print("x1 =", x1)
    print("x2 =", x2)
else:
    print("Roots are imaginary.")

OUTPUT :
Enter a: 1
Enter b: -5
Enter c: 6
Roots are: 
x1 = 3.0
x2 = 2.0
