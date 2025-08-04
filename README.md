print("Benedict's Calculator")
print("+,-,*,/")
c=input("Enter the operation you like:")
a=int(input("Enter the first number:"))
b=int(input("Enter the second number:"))
if c=='+':
    print(f"the number we get is {a+b}")
elif c=='-':
    print(f"the number we get is {a-b}")
elif c=='*':
    print(f"the number we get is {a*b}")
elif c=='/':
    print(f"the number we get is {a/b}")
else:
print("You have typed an unknown command!")
