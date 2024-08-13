# CODSOFT_1
# Task 1 : Simple Calculator
# Asking the user to enter the operation choice
print("Enter the operation you want to perform\n 1. Addtion\n 2. Substraction\n 3.mutliplication\n 4. Division")
choice = int(input("enter an operation choice :"))

# Inputting  two numbers from the user
a = int(input("enter first number : "))
b = int(input("Enter second number :"))

# Performing operation as per the user's choice
if choice==1:
    c=a+b
    print(a,"+",b,"=",c)
elif choice == 2:
    d=a-b
    print(a,"-",b,"=",d)
elif choice == 3:
    e = a*b
    print(a,"*",b,"=",e)
elif choice == 4:
    f = a/b
    print(a,"/",b,"=",f)
else :
    print("Invalid choice")
