# Python-Program-for-How-to-check-if-a-given-number-is-Fibonacci-number.py
n=int(input("Enter the number: "))

a=1
b=0
c=0
if n==0 or n==1:
    print("Yes")
else:
    while c<n:
        c=a+b
        b=a
        a=c
    if c==n:
        print("Yes")
    else:
        print("No")
 
