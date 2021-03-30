# FaultyCalculator
## It is an faulty calculator  which can perform all calculations correctly except  on given numbers and operations
#here we make a faulty calculator which take operator and two values from user perform all calculation correctly except<br>
#45*3=555, 56+9=77, 56/6=4 <br>
print("enter the operator (+, -, *, /)")<br>
ope=input()<br>
print("Enter two operands/values for performing calculation: ")<br>
a=float(input("Enter first number :"))<br>
b=float(input("Enter second number: "))<br>
if a==45 and b==3 and ope=="*":<br>
    print(a,"*",b,"=","555") <br>
elif ope=="*":<br>
    print(a, "*", b ,"=", a*b)<br>
elif a==56 and b==9 and ope=="+":<br>
    print(a,"+",b,"=","77")<br>
elif ope=="+":<br>
    print(a, "+",b ,"=",a+b)<br>
elif a==56 and b==6 and ope=="/":<br>
    print(a,"/",b,"=","4")<br>
elif ope=="/":<br>
    print(a, "/", b , "=" ,a/b)<br>

elif ope=="-":<br>
    print(a, "-", b ,"=", a-b)<br>


else:<br>
    print("invalid operator\n")<br>


    
