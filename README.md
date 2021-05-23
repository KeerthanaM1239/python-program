# python-program
amstrong number


n=153
n1=n
res=0
while n!=0:
  num=n1%10
  res=num**3
  n1//=10
if res==n:
  print("It is armstrong number")
 else:
  print("It is not armstrong number")
