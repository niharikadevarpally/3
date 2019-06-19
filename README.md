# 3
import sympy
num = int(input("enter num:"))
list1 = [i for i in sympy.primerange(2,num) if num % i == 0]
print(list1[-1])
