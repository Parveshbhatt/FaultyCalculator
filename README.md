# FaultyCalculator
It is an faulty calculator  which can perform all calculations correctly except  on given numbers and operations
#here we make a faulty calculator which take operator and two values from user perform all calculation correctly except
#45*3=555, 56+9=77, 56/6=4
print("enter the operator (+, -, *, /)")
ope=input()
print("Enter two operands/values for performing calculation: ")
a=float(input("Enter first number :"))
b=float(input("Enter second number: "))
if a==45 and b==3 and ope=="*":
    print(a,"*",b,"=","555") 
elif ope=="*":
    print(a, "*", b ,"=", a*b)
elif a==56 and b==9 and ope=="+":
    print(a,"+",b,"=","77")
elif ope=="+":
    print(a, "+",b ,"=",a+b)
elif a==56 and b==6 and ope=="/":
    print(a,"/",b,"=","4")
elif ope=="/":
    print(a, "/", b , "=" ,a/b)

elif ope=="-":
    print(a, "-", b ,"=", a-b)


else:
    print("invalid operator\n")


    
