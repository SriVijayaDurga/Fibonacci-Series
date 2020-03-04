# Fibonacci-Series
#shortcut
n = int(input())
a, b = 0, 1
for i in range(0, n):
  print(a)
  a, b = b, a+b
  
# Using Genetaror
def fib(n):
  a, b = 0, 1
  for i in range(0,n):
    yield a
    a, b = b, a+b
    
    
for f in fib(7):
  print(f)
