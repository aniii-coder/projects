# Simple calculator
def add(a,b):
    return a+b
def subt(a,b):
    return a-b
def mul(a,b):
    return a*b
def div(a,b):
    return a/b 
x = int(input("Enter num1:-"))
y = int(input("Enter num2:-"))
print("select opearation")
print("1.add")
print("2.subt")
print("3.mul")
print("4.div")
a = int(input("Enter the number"))
if a <= 4:
   if a == 1:
    print(add (x,y))
   elif a == 2:
    print(subt (x,y))
   elif a == 3:
    print(mul (x,y))
   else:
    print(div (x,y))
else:
    print("ENTER NUMBER BETWEEN 1-4")
