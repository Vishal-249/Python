neil=int(input())
a = list(map(int, input().split()))
key=int(input())
fg=0
for i in range(neil):
    for j in range(0,neil):
        if(a[i]!=a[j]):
            if(a[i]+a[j]==key):
                fg+=1
if(fg==0):
    print("No")
else:
    print("Yes")
