print("My first project")
n=int(input("Enter the number"))
if n % 2==0:
    print("Number id Even")
else:
    print("Number is Odd")
def factorial(n):
    if n==0 or n==1:
        return(n)
    else:
        return(n*factorial(n-1))
result=factorial(6)
print("FACT IS",result)