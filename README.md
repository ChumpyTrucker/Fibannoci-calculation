# Fibannoci-calculation
I will create a code which will do a calculation using a Range function to see Fibannoci theory calculation.
#Fibannoci theory
#Range function
def fib(number):
  a = 0
  b = 1
  for i in range(number):
    yield a
    temp = a
    a = b
    b = temp + b

#for x in fib(100):
  #print(x)

#List
def fib2(number):
  a = 0
  b = 1
  result = []
  for i in range(number):
    result.append(a)
    temp = a
    a = b
    b = temp + b
  return result

print(fib2(100))

