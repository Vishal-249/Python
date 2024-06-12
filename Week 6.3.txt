t=int(input())
n=int(input())
l1=list()
for i in range(n):
    a=int(input())
    l1.append(a)
m=int(input())
l2=list()
for i in range(m):
    b=int(input())
    l2.append(b)

for i in l1:
    if i in l2:
        print(i,end=' ')
    else:
        continue
