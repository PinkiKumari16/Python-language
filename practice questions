# # ***************   Armstrong Number     ***************
# number=input("enter the number :")
# l=len(number)
# number=int(number)
# num=number
# sum1=0
# while num>0:
#     sum1+=((num%10)**l)
#     num//=10
# if number==sum1:
#     print("yes")
# else:
#     print("no")

# #***************    Perfect Square   ***********
# number=int(input("enter the number :"))
# i=1
# flag=0
# while True:
#     if (i**2)==number:
#         flag=1
#         break
#     elif (i**2)<number:
#         i+=1
#         continue
#     else:
#         break
# if flag==1:
#     print("YES")
# else:
#     print("NO")

# #  ************    Ugly Number   ***********
# number=int(input("enter the number :"))
# if (number % 2 == 0) or (number % 3 == 0) or (number % 5 ==0):
#     print("yes")
# elif number==1:
#     print("yes")
# else:
#     print("no")
    
# # ***********   Strong Number  ***********
# number=int(input("enter the number :"))
# num=number
# sum1=0
# while num>0:
#     digit=num%10
#     fac=1
#     j=2
#     while j<=digit:
#         fac*=j
#         j+=1
#     sum1+=fac
#     num//=10
# if sum1==number:
#     print("yes")
# else:
#     print("no")


# Q22 Find 2nd and 3rd max in a single code from 4 numbers
# a,b,c,d=map(int,input().split())
# S_MAX=0
# T_MAX=0
# if a>b:
#     max1=a
#     sec1=b
# else:
#     max1=b
#     sec1=a
    
# if c>d:
#     max2=c
#     sec2=d
# else:
#     max2=d
#     sec2=c
    
# if max1>max2:
#     if max2>sec1:
#         S_MAX=max2
        
#         if sec1>sec2:
#             T_MAX=sec1
#         else:
#             T_MAX=sec2
#     else:
#         S_MAX=sec1
#         T_MAX=max2

# else:
#     if max1>sec2:
#         S_MAX=max1
        
#         if sec1>sec2:
#             T_MAX=sec1
#         else:
#             T_MAX=sec2

#     else:
#         S_MAX=sec2
#         T_MAX=max1
# print("SECOND_MAX :",S_MAX)
# print("THIRD_MAX :",T_MAX)


# # Q21 Make a dynamic code for the following list
# # (ex: [2,4,3,1,4,9] into [4,2,1,3,9,4])
# # (ex: [2,4,3,1,7] into [4,2,3,7,1])
# # l=[2,4,3,1,4,9]
# l=[2,4,3,1,7]
# i=0
# j=len(l)-1
# while i < j:
#     if j-i==1:
#         l[i],l[i+1]=l[i+1],l[i]
#     else:
#         l[i],l[i+1]=l[i+1],l[i]
#         l[j],l[j-1]=l[j-1],l[j]
#     i+=2
#     j-=2
# print(l)

# # Q19 Divide a given mobile number as shown: 739-567-3456
# number=input("enter your mobile number :")
# i=1
# s=0
# ans=""
# while i<=2:
#     ans+=number[s:s+3]+"-"
#     s+=3
#     i+=1
# print(ans+number[s:])


# #Q:18 Accept the temperature form the user and check if the given temperature is
# # Celsius then you have to change it in Fahrenheit and if it is in Fahrenheit then
# # change in Celsius otherwise display “Please Enter Valid Unit”.
# temp=float(input("enter temperature :"))
# unit=input("enter the unit (F,C) :")
# if unit=="F":
#     C=(temp-32)*5/9
#     print("Temperature in Celsius :",C)
# elif unit=="C" :
#     F = (temp * 9/5) + 32
#     print("Temperature in Fahrenheit :",F)
# else:
#     print("Please Enter Valid Unit")


# # Q:17 Find the minimum digit from the user input.
# number=int(input("enter the number :"))
# mini=number%10
# while number>0:
#     mini=min(mini,number%10)
#     number//=10
# print(mini)    

# Q:16 write a logical expression for the following:
# A is greater than B and C is less than and equal to D 
# A>B and C<=D


# # Q: 15 Check if the user number has a middle number or not. If it has then you
# # have to print “odd winner” otherwise “even winner”.
# number=input("enter the number :")
# l=len(number)
# if l%2!=0 and l!=1:
#     print("number has middle number ")
#     mid=int(number[l])
#     if mid%2==0:
#         print("even winner")
#     else:
#         print("odd winner")
# else:
#     print("number has not middle number")


# Q:14 Write a program to display “Hello” if user input is multiple of 5 and 8
# otherwise it is “bye”.
# num=int(input("enter the number :"))
# if num%5==0 and num%8==0:
#     print("HELLO")
# else:
#     print("BYE")

# # Q:13 Find 2nd max from 3 numbers
# a,b,c=map(int(input("enter three number :")))
# S_MAX=0
# if (a>b and a<c) or (a<b and a>c):
#     S_MAX=a
# elif (b>a and b<c) or (b<a and b>c):
#     S_MAX=b
# else:
#     S_MAX=c
# print("SECOND MAX IS :",S_MAX)

# # Q12 find how many pairs (sum) can be formed from a number
# # (Hint : 3=3+0,2+1 and don’t print duplicate pairs)
# # Eg:- 3 = 2,1
# number=int(input("enter the number :"))
# i=0
# while i<=number/2:
#     print(i,number-i)
#     i+=1


# # Q11 check whether a number is automorphic or not;
# # Hint : if a number n has a square and it also ends with n
# # Eg:-5 is automorphic as its square 25 also ends with 5
# num=int(input("enter the number :"))
# squ=num**2
# if (num)==(squ%10):
#     print("Automorphic")
# else:
#     print("Not Automorphic")


# # Q10 check valid credit card
# # ● It will start with 4, 5 and 6
# # ● It will be 16 digits’ long
# # ● Numbers must contain only digits
# # ● It may have digits in four groups separated by '-'
# # ● It must not use any other separator like space or underscore
# # ● It must not have 4 or more consecutive same digits

# c_number=input("enter your credit-card number :")
# if len(c_number)==19:
#     if c_number[0]=="4" or c_number[0]=="5" or c_number[0]=="6":
#         i=0
#         n=0
#         s=0
#         while i<len(c_number):
#             if i>="0" and i<="9":
#                 n+=1
#             elif i=="-":
#                 s+=1
#         if n==16 and s==4:
#             if (c_number[4]=="-") and (c_number[9]=="-") and (c_number[14]=="-"):
#                 i=0
#                 c=0
#                 p=0
#                 while i<len(c_number)-1:
#                     if c_number[i]==c_number[i+1]:
#                         c+=1
#                         if c==4:
#                             p=1
#                             break
#                     else:
#                         c=0
#                     i+=1
#                 if p==0:
#                     print("Valid Credit card")
#                 else:
#                     print("Invalid Credit card number")
#             else:
#                 print("Invalid Credit card number") 
#         else:
#             print("Invalid Credit card number")
#     else:
#         print("Invalid Credit card number")
# else:
#     print("Invalid Credit card number")


# # Q8 valid date of birth using if else
# print("enter your birthday date :")
# dd=int(input("date :"))
# mm=int(input("month :"))
# yy=int(input("year :"))
# if (dd>=1 and dd<=31) and (mm>=1 and mm<=7) and (mm%2==1):
#     print("Valid date :",dd,"-",mm,"-",yy)
# elif (dd>=1 and dd<=31) and (mm>=8 and mm<=12) and (mm%2==0):
#     print("Valid Date :",dd,"-",mm,"-",yy)
# elif (dd>=1 and dd<=30) and (mm==4 or mm==6 or mm==9 or mm==11):
#     print("Valid Date :",dd,"-",mm,"-",yy)
# elif (dd>=1 and dd<=29) and (mm==2) and (yy%4==0 and yy%400==0 and yy%100!=0):
#         print("Valid and Leep Year :",dd,"-",mm,"-",yy)
# elif (dd>=1 and dd<=28) and (mm==2):
#     print("Valid Date :",dd,"-",mm,"-",yy)
# else:
#     print("IN-Valid Date ")


# Q7. Which of the following is an example of concatenation?
# a. 6 + 3
# b. '6' + '3'
# c. 'a' + 'b' + 'c'
# answer : 'B and C'

# Q6.
# s='My' 
# s1='Blog'
# s2=s[:1]+s1[len(s1)-1:]
# print(s2)

# # Q5. 
# s='Welcome to My Site https://nayaksworld.com '
# print(s.find('come'))
# print(s.find('o'))
# print(s.find('o', 10, 20))
# print(s.find('o', 5, 10))

# # Q4- Write a program to print a solid square pattern of N rows and N columns
# # using the asterisk character (*), where integer N is given as an input.
# n=int(input("enter the num :"))
# i=1
# while i<=n:
#     print("*"*i)
#     i+=1
