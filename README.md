# patterns-numeric-2-2type-
a=[]
t=int(input())
for i in range(t):
  x=[]
  for j in range(t):
    if i>=j:
      x.append(i+1)
    else:
      x.append(" ")
  a.append(x)
for i in a:
  print(*i,end=" ")
  print()
