# Ch1
print("Vanakkam Tamilnadu")![Screenshot_20231001_185545_Pydroid 3](https://github.com/CHARLESJESU/Ch1/assets/146636808/57fda768-77f7-42f6-855e-89547ec1e873)



n=int(input("Enter a number"))
print(n*n)
print(n*n*n)
print(2**n)
![Screenshot_20231001_185625_Pydroid 3](https://github.com/CHARLESJESU/Ch1/assets/146636808/6e3543eb-b4fd-448f-a4d3-1c573c6a064c)


print("*")
print("**")
print("***")
print("****")
![Screenshot_20231001_185752_Pydroid 3](https://github.com/CHARLESJESU/Ch1/assets/146636808/71027673-b227-49e9-8d81-01f5924bca9f)



n=input("What's your name?")
a=int(input("How old are you?"))
c=input("What's your favorite color?")
h=input("What's your favorite hobby?")
![Screenshot_20231001_185911_Pydroid 3](https://github.com/CHARLESJESU/Ch1/assets/146636808/0859ba67-466c-46ef-b700-447b897ece26)


n=int(input("Enter a number"))
if n%2==0:
    print("evern")
else:
    print("odd")![Screenshot_20231001_190008_Pydroid 3](https://github.com/CHARLESJESU/Ch1/assets/146636808/117ac580-c604-4ce3-98fb-209860b40c4f)
![Screenshot_20231001_190053_Pydroid 3](https://github.com/CHARLESJESU/Ch1/assets/146636808/58fda79f-19e2-434b-8671-0ee05bad793b)



n=int(input("Enter a number"))
for i in range(1,n+1):
    print(i)
![Screenshot_20231001_190426_Pydroid 3](https://github.com/CHARLESJESU/Ch1/assets/146636808/963f556a-ef86-45d9-8e3a-bb56e40d840c)


s=int(input())
d=int(input())
e=int(input())
for i in range(s,e,d):
    print(i,end=' ')
    ![Screenshot_20231001_190500_Pydroid 3](https://github.com/CHARLESJESU/Ch1/assets/146636808/729357e4-8e80-4bb7-a64d-914e8114e86c)


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
