# Ch1
print("Vanakkam Tamilnadu")


n=int(input("Enter a number"))
print(n*n)
print(n*n*n)
print(2**n)


print("*")
print("**")
print("***")
print("****")


n=input("What's your name?")
a=int(input("How old are you?")
c=input("What's your favorite color?")
h=input("What's your favorite hobby?")


n=int(input("Enter a number"))
if n%2==0:
    print("evern")
else:
    print("odd")


n=int(input("Enter a number"))
for i in range(1,n+1):
    print(i)


s=int(input())
d=int(input())
e=int(input())
for i in range(s,e,d):
    print(i,end='')

n=int(input())
sum=0
for i in range(1,n+1):
    sum+=i
print(sum)

n=int(input())
for i in range(1,11):
    p=n*i
    print(i,"*",n,"=",p)

n=int(input())
if n>1:
    for i in range(2,n):
        if n%i==0:
            print(n,"is not a prime number")
            break
    else:
        print(n,"is a prime number")
