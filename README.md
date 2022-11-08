# faulty-Calculator
a=int(input("enter the value:"))
b=int(input("enter the another value: "))
operator=input("enter the operator(+,-,*,/) : ")
if(a==56 and b==9 and operator=='+'):
    print("77")
elif(a==45 and b==3 and operator=='*'):
    print("555")
elif(a==56 and b==6 and operator=='/'):
    print("4")
elif(operator=='+'):
    c=a+b
    print(c)
elif(operator=='-'):
    c=a-b
    print(c)
elif(operator=='*'):
    c=a*b
    print(c)
elif(operator=='/'):
    c=a/b
    print(c)
