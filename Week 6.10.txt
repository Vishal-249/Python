a=[]
n=int(input())
for i in range(n):
    a.append(int(input()))
f=int(input())
l=1
t=False
c=0
for i in a:
    if i==f:
        print("%d is present at location %d."%(f,l))
        c+=1
    l+=1
if c!=0:
    print("%d is present %d times in the array."%(f,c))
else:
    print("%d is not present in the array."%f)
