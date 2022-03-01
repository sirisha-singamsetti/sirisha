n=int(input())
l=[]
for i in range(n):
    x=int(input())
    l.append(x)
l2=[]
c=0
for i in l:
    for j in l:
        if(i==j):
            c=c+1
    if(c%2!=0):
        l2.append(i)
    c=0
l3=[]
l3.append(l2[0])
for i in l2:
    if(l2[i]!=l3[-1]):
        l3.append(l2[i])
print(l)
print(l3)
