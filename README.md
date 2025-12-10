# Python-28
Write a Python program to check whether the number entered by user is even or odd.
num=int(input("Enter any number:"))
flag=num%2
if flag ==0:
    print(num,"ia an even number")
elif flag ==1:
    print(num,"is an odd number")
else:
    print("Error,Invalid input")
Output
Enter any number:10Enter any number: 5
5 is a prime number
