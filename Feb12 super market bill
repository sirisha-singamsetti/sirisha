soaps=100
chocolates=150
biscuits=100
essentials=200
fruits=500
cno=int(input("enter customer number:"))
cname=input("enter customer name:")
s=int(input("no of soaps:"))
c=int(input("no of chocolates:"))
b=int(input("no of biscuits:"))
e=int(input("no of essentials:"))
f=int(input("no of fruits:"))
bill=(soaps*s)+(chocolates*c)+(biscuits*b)+(essentials*e)+(fruits*f)
print("your bill is:",bill)
if(bill>5000):
    disc=bill*10/100
    tax=bill*10/100
elif(bill>3000):
    disc=bill*8/100
    tax=bill*10/100
elif(bill>2000):
    disc=bill*5/100
    tax=bill*18/100
else:
    disc=bill*3/100
    tax=bill*18/100

finalbill=bill-disc+tax
print("your final bill is:",finalbill)
