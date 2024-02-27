# highest-number
'''
# approach1
n=[2,7,1,9,10]
max_number=max(n);
print("max number:",max_number)
'''
'''
# approach2
n=int(input())
a=list(map(int,input().split()))
m=0
for i in range(n):
  if a[i]>m:
    m=a[i]
print(m)
'''
'''
# approach3
n=int(input())
a=list(map(int,input().split()))
m=0
for i in range(n):
  if a[i]>m:
    m=a[i]
ind=a.index(m)
print(m,ind)
'''
'''
# approach4
n=int(input())
a=list(map(int,input().split()))
m=0
for i in a:
  if i>m:
    m=i
ind=a.index(m)
print(m,ind)

'''
'''
# approach5
n=int(input())
a=list(map(int,input().split()))
res=0
for i in range(n):
  if a[i]%2==0:
    res=res+a[i]
print(res)
'''
#approach6
n=int(input())
a=list(map(int,input().split()))
res=0
for i in a:
  if i%2==0:
    res=res+i
print(res)
