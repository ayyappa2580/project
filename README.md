# Q.no-1 swapping the two numbers in list
# a=[10,20,30]
# b=[10,20,40]
# c=a
# a=b
# b=c
# print(a,b,c)

# Q.no-2 find the length of list
# a=["ayyappa"]
# print(a)
# b=tuple(a)
# print(b)
# print(len(a[0]))

# Q.no-3 program to interchange first value in list only
# lst=[1,2,3,4,5]
# print('before the list------>{}'.format(lst))
# p=lst[-1]
# s=lst[0]
# n=p
# p=s
# s=n
# lst[-1]=p
# lst[0]=s
# print("after the list---->{}".format(lst))

# Q.no-4 Python | Reversing a List
# a=[10,20,30]
# print(a)
# print(a[::-1])

# Q.no-5 Python program  Multiply all numbers in the list
# a=[10,20,30,40,50]
# m=1
# for i in range(0,len(a)):
#     print(a[i])
#     m=m*a[i]
# print("sum of values={}".format(m))

# Q.no-6 Python program to find smallest number in a list
# lst=[10,20,220,1]
# kvrmax=220
# kvrmin=1
# for val in lst:
#     if kvrmax<val:
#         kvrmax=val
# print(kvrmin)

# Q.no-7 Python program to find largest  number in a list
# lst=[100,2009,209393,191]
# ayyappamax= 100
# ayyappamin=209393
# for val in lst:
#     if ayyappamin<val:
#         ayyappamax=val
# print(ayyappamin)

#Q.no-8 Python program to print all negative numbers in a range
# a=int(input("enter a number :"))
# b=int(input("enter a number :"))
# for i in range(a,b):
#     if i<0:
#         print(i)

# Q.no-9 Python program to print all positive numbers in a range
# a=int(input("enter a number u want positive number:"))
# b=int(input("enter a number u want positive number:"))
# for i in range(a,b):
#     if i>0:
#      print(i)

# Q.no-10 Python program to find second largest number in a list
# a=[60,20,30,2,1,6,4,17,70]
# s=sorted(a)
# print(s)
# print("second largest number:{}".format(s[-2]))

# Q.no-12 Python program to print even numbers in a list
# list=[10,20,30,40,11,50]
# for num in list:
#     if num%2==0:
#         print(num)

# Q.no-13 Python program to print odd numbers in a List
# lst=[1,2, 3, 4,5,6,7,8, 9, 11, 13, 15, 17, 19, 21, 23, 25, 27, 29, 31, 33, 35, 37, 39, 41, 43, 45, 47, 49]
# for num in lst:
#     if num&2==0:
#         print(num)

# Q.no-14 Python program to print all even numbers in a range
# a=int(input("enter a number:"))
# b=int(input("enter end number:"))
# for num in range(a,b+1):
#     if num%2==0:
#         print(num)

# Q.no-15 Python program to print all odd numbers in a range
# start=int(input("enter a number:"))
# end=int(input("Enter end number:"))
# for num in range(start,end+1):
#     if num%2==1:
#         print(num)

# Q.no-16 Python program to print positive numbers in a list
# list=[1,-1,2,22,-33,-333,-33,-4883,-111,9811]
# for i in list:
#     if i>0:
#         print(i)

# Q.no-17 Python program to print negative numbers in a list
# list=[1,-1,2,22,-33,-333,-33,-4883,-111,9811]
# for i in list:
#      if i<0:
#          print(i)

# Q.no-18 Python program to print all positive numbers in a range
# end=start=int(input("Enter start number:"))
# int(input("enter end number:"))
# for num in range(start,end+1):
#     if num>0:
#         print(num)

# Q.no-19 Python program to print all negative numbers in a range
# end=start=int(input("Enter start number:"))
# int(input("enter end number:"))
# for num in range(start,end+1):
#     if num<0:
#         print(num)

# Python – Remove empty List from List
# lst=[1,2,(),3,4,[],66,7,8,[],[],()]
# i=0
# while i<len(lst):
#     if lst[i]==[]:
#         del lst[i]
#     else:
#         i=i+1
# print(lst)

# Python | Program to print duplicates from a list of integers
# lst=[1,2,3,4,5,5,5,5,5,66,6,7,8]
# element_count={}
# for x in lst:
#       if x in element_count:
#           element_count[x]=+1
#       else:
#           element_count[x]= 1
# print("duplicate values :")
# for item, count in element_count.items():
#     if count>1:
#         print(item)

# Python | Count occurrences of an element in a list
# lst=[1,86,76,86,1,1,2,23,32,23,86]
# cnt=0
# m=int(input("enter the index value you want count:"))
# for i in range(0,len(lst)):
#     if lst[m]==lst[i]:
#         cnt=cnt+1
# print(lst.count(86))
