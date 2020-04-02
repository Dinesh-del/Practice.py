Print("Hello python")
a=5
print (a)

s="google"
d={}
print(d)

for i in s:
    print(i)
    d[i]=d.get(i,0)+1
    print(d)

s="python programming"
d={}
print(d)

for i in s:
    print(i)
    d[i]=d.get(i,0)+1
    print(d)


 dict={"benelli":350000,"hyosung":400000,"duke 790":2100000}
 print(dict)

 def bikes(dict):
     if name in dict:
         print("The price of the bike: ",{dict.values()})
     else:
        print("would you like to check with available bikes: ""(benelli:350000,hyosung:400000,duke 790:2100000)")
     choice = input("Enter yes or no")
     if choice == 'yes':
         print("The price of the bike: ",{dict.values})
     else:
         print("Sorry, we can't help you with this")
 name = input("Enter the name of the bike: ")
 bikes(dict)





 l1=[1,2,3,4,5]
 i=0
 while i<len(l1):
     l1[i]=l1[i]+100
     i=i+1
     print(l1)

def find_sum(lst):
     a=sum(lst)
     print(a)

lst= [1,2,3,4,5]

for i in lst:
    input("Enter the no:").split(',')
print(lst)

find_sum([1,2,3,4,5])


def reverse_slicing(name):
    return name[::-1]
     if name == "hpmiurt":
        print("Reverse string using slicing=",reverse_slicing(name))

res=reverse_slicing("hpmiurt")
print(res)

def reverse_for_loop(name):
    N1 = " "
    for i in name:
        N1 = i+N1
    return N1

#     if name == "illeneb":
#         print("Reverse string using reverse_for_loop=",reverse_for_loop)
#
# res = reverse_for_loop("illeneb")
# print(res)
#
# str = "gnusoyh"
# def reverse_while_loop(str):
#     S1=" "
#     length = len(str)-1
#     while length >= 0:
#         S1 = S1+str[length]
#         length = length-1
#     return S1
#
#     if str == "gnusoyh":
#         print("Reverse string using reverse_while_loop=",reverse_while_loop("gnusoyh"))
#
# res = reverse_while_loop("gnusoyh")
# print(res)
#
#
# def reverse_join_iter(str):
#     S1 = " ".join(reversed(str))
#     return S1
# res = " ".join(reversed("ekud"))
# print(res)
#
#
# def reverse_list(str):
#     list1 = list(str)
#     list1.reverse()
#     return " ".join(list1)
#
# res = reverse_list("anotyad")
# print(res)
#
# # def reverse_recursion(s):
# #     if len(s) == 0:
# #         return (s)
# #     else:
# #         return reverse_recursion(s[1:]+s[0])
# #
# # res = reverse_recursion("relpirtteerts")
# # print(res)
#
#
# a = [25,35,45,55,86,92,88,32]
#
# n = 127
#
# for i in a:
#     sub = n-i
#
#     if sub in a:
#         print(sub,i)
#
# a = [1,2,3,4,5,5,6,7,8,1,3,5]
#
# list = []
# idx = {}
#
# for i in a:
#     if i not in list:
#         list.append(i)
#     else:
#         idx[i]=a.index(i)
#
#
# print(idx)
#
a = [1,2,3,4,5,6,6,7,8,1,3,5]

list = []
idx = {}

for i in a:
    if i not in list:
        list.append(i)
    else:
        idx[i]=a.index(i)


print(idx)
#
# #
#
#
# class employee:
#
#     office = "amazon"
#
#     def _init_ (self, id, name, salary):
#         self.id = id
#         self.name = name
#         self.salary = salary
#
#     def display(self):
#         print("Employee id:",self.id)
#         print("Employee name:",self.name)
#         print("Employee salary:",self.salary)
#
# n = int(input("how many times"))
#
# for i in range (n):
#     id = int(input("Enter the number"))
#     name = input("Enter the name of the employee")
#     salary = float(input("Enter the salary"))
#
# s = employee(id,name,salary)
# s.display()
#
#
# class employee:
#
#     office = "amazon"
#
#     def _init_(self, id, name, salary):
#         self.id = id
#         self.name = name
#         self.salary = salary
#
#     def display(self):
#         print("employee id:",self.id)
#         print("employee name:",self.name)
#         print("employee salary:",self.salary)
#
# n = int(input("how many times"))
# i = 0
#
# while (i<=n):
#
#     id = int(input("Enter the id"))
#     name = input("Enter the name")
#     salary = float(input("Enter tha salary"))
# s = employee(id, name, salary)
# s.display()
# i=i+1
#
#
# def welcome():
#     print("Amazon welcomes you Dinesh")
# welcome()
#
#
# def welcome(name):
#     print(name)
# welcome("Amazon welcomes Dinesh to banglore")
# welcome("Amazon cordially invites jeff bezos to banglore office")
#
# num = int(input("Enter the number"))
# def square(i):
#     i=0
#     while i<=num:
#         print(num*num)
#         i=i+1
# res = square('i')
# print(res)
#
# def square(num):
#     print("square of",num,":",num*num)
# square(5)
# square(25)
# square(50)
# square(75)
# square(100)
#
# def add(x,y):
#     return(x+y)
# res = add(10+20,20+40)
# print(res)
#
# def num(x):
#     if x%2==0:
#         print("Given num is even")
#     else:
#         print("Given num is odd")
# num(4)
# num(6)
# num(9)
#
# def fac(num):
#     if (num==0 or num==1):
#         return 1
#     else:
#         return num*fac(num-1)
# num = int(input("Enter the num"))
# res = fac(num)
# print(res)
#
# def division(num):
#     if num%3 == 0:
#         print("Number is divisible by three")
#     else:
#         print("Number is not divisible by three")
# division(3)
# division(6)
# division(27)
# division(67)
# division(77)
#
# def sum_sub(a,b):
#     sum = a+b
#     sub = a-b
#     return sum,sub
# res = sum_sub(120,30)
# print(res)
#
# def add(a,b):
#     return(a+b)
# res = add(198,287)
# print(res)
#
# def hello(name,msg):
#     print(name,msg)
#
# hello(name = "Dinesh",msg = "unfortunately you lost your lap")
# hello(msg = "you do have your python class by evening",name = "Dinesh")
# hello(name = "Sanjai and Dinesh",msg = "are good friends since 13 years")
#
# def hello(name = "Dinesh"):
#     print(name, "is a die hard fan of valentino")
#
# hello("Dinesh")
# hello("sanjai")
#
# def display(*bikes):
#     for i in bikes:
#         print(i)
# display("Benelli","Hyosung","Ducati panigale","CBR")
#
# name = "Valentino"
# number = int(46)
# def fun():
#     print(number,"of",name)
#     print(name,"is",number)
# fun()
#
# def fun():
#     name = "lorenzo"
#     number = int(93)
#     print(number,"of",name)
#     print(name,"is",number)
# fun()
#
#
# def recursion(num):
#     if num == 0 or num == 1:
#         return 1
#     else:
#         return num*fac(num-1)
# num = int(input("Enter the number"))
# res = recursion(num)
# print(res)
#
# str = "Cannabis marijuana charas malana"
# str_list = str.split(' ')
# print(str_list)
#
# list = ["cannabis","marijuana","charas","malana"]
# list_str = " ".join(list)
# print(list_str)
# #
# d = {1:10,2:20,3:30}
# print(d)
# d.update({5:10,10:20,15:30})
# print(d)
#
# dic1 = {"benelli":350000}
# dic2 = {"panigale":700000}
# dic3 = {"duke 790":810000}
# dic4 = {}
# for items in (dic1,dic2,dic3):
#     dic4.update(items)
# print(dic4)
#
# print("twinkle twinkle little star\n\t how i wonder what you are!\n\t\t up above the word so high\n\t\t\t like a diamond in the sky")


# import sys
# print("python version")
# print(sys.version)
# print("version info")
# print(sys.version_info)
#
# import datetime
# now = datetime.datetime.now()
# print("Current date and time")
# print(now.strftime("%y-%m-%d%H:%M:%S"))
#
# from math import pi
# r = float(input("Enter the radius of the circle"))
# print("The area of the circle with radius" +str(r)+ "is:"+str(pi*r**2))
#
# fname = input("Enter the first name")
# lname = input("Enter the last name")
#
# print("This is:" + lname + " " + fname)
#
# values = input("Enter the numbers with commas")
# list = values.split(",")
# tuple = tuple(list)
# print("list:",list)
# print("tuple",tuple)
#
# names = ["Dinesh","Vijai","Kalpana","rajamani"]
# print("This is:",names[0]+names[-1])
#
# name = "Valentino rossi"
# number = 46
# print ('%s %d' % (name,number))
#
# print('%s is %d years old' % ("Dinesh",25))
#
# examination_st_date = (23,2,2020)
#
# print("The examination will start from:%i/%i/%i" % examination_st_date)
#
# a = int(input("Enter the number"))
# n1 = int('%d'%a)
# n2 = int('%d%d'%(a,a))
# n3 = int('%d%d%d'%(a,a,a))
# n4 = int('%d%d%d%d'%(a,a,a,a))
# n5 = int('%d%d%d%d%d'%(a,a,a,a,a))
# print(n1+n2+n3+n4+n5)
#
# import calendar
#
# year = int(input("Enter the year"))
# month = int(input("Enter the month"))
# print(calendar.month(year,month))
#
# from datetime import date
#
# fdate = date(2020,2,23)
# ldate = date(2020,2,29)
# delta = ldate-fdate
# print(delta.days)


def sum(a,b):
    return(a+b)
a = int(5)
b = int(4)
res = sum(a,b)
print(res)

#
# list = []
# len = int(input('How many numbers: '))
# for n in range(len):
#     numbers = int(input('Enter number '))
#     list.append(numbers)
#     res = (sum(list))
#     print(res)
