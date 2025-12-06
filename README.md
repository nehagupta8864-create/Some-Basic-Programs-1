# Some-Basic-Programs-1
Here i will upload my pratice python codes daily.

# # 15  factorial number

# num= int(input("Enter the number for which u want to know the factorial: "))
# fact=1
# if (num<0):
#     print("factorial of 0 does not exist.")
# if (num==0):
#     print(f"Factorial of 0 is : {1}")
# if (num>0):
#     for i in range(1,num+1):
#         fact= fact*i

# print(f"The factorial if the given number is {fact}.")

# def Fact(a):
#     if a==0:
#         return 1
#     else:
#         return (a * Fact(a-1))

# num= int(input("Enter a number here: "))
# Result= Fact(num)
# print(f"The factorial of the given number is {Result}.")

# # 16  printing the table 
# for i in range(1,21):
#     print(f"52 X {i} = {52*i}")

# n= int(input("Enter the number here for printing table: "))
# for i in range(1,21):
#     print(f"{n} X {i} = {n*i}")

# n= int(input("Enter the number here for printing table: "))
# i=0
# while i <=20:
#     print(f"{n} X {i} = {n*i}")
#     i+=1

# # 17 fibonacci Sequence

# a=0
# b=1
# num= int(input("Enter a number to obtain fibbonachi sequence: "))

# if (num==1):
#     print(a)
# else:
#     print(a)
#     print(b)
#     for i in range(2,num+1):
#         c=a+b
#         a=b
#         b=c
#         print(c)

# # 18   Armstrong number

# num= int(input("Enter a number here: "))
# sum=0
# temp=num

# while temp>0:
#     digit= temp%10
#     cube= digit**3
#     sum= sum+cube
#     temp //=10

# if sum==num:
#     print("It is an armstrong number.")
# else:
#     print("it is not an armstrong number.")


# num= int(input("Enter a number here: "))
# sum=0
# temp=num

# while temp>0:
#     digit= temp%10
#     cube= digit**3
#     sum= sum+cube
#     temp //=10

# if sum==num:
#     print("It is an armstrong number.")
# else:
#     print("it is not an armstrong number.")

# num= int(input("Enter a number here: "))
# order= len(str(num))
# sum=0
# temp=num

# while temp>0:
#     digit= temp%10
#     cube= digit**order
#     sum= sum+cube
#     temp //=10

# if sum==num:
#     print("It is an armstrong number.")
# else:
#     print("it is not an armstrong number.")
