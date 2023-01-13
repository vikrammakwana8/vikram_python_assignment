# vikram_python_assignment
 
  (1)How to the python code Structure work?
 
 
 (2)How to create variable inpython?
 var=10
 
 (3)How to take user input?

user_input=input("enter the value:---")

(4) How to check the type of variable dynamically.

variable_1=10
variable_2="good"
variable_3=True

print(type(variable_1))
print(type(variable_2))
print(type(variable_3))

(5)W.A.P tofind greater and less than number using If_else

number=10
if number>5:
  print("number is greater then 5")
elif number==5:
  print("number is equal to 5")

else:
  print("number is less then 5")  

(6) W.A.P to find prime number using if_else

count=0
n=10

for i in (2,n-1):
  if n%i==0:
    count =count+1
    
if count>0:
  print("number is not prime")

else:
  print("number is prime")

(7)W.A.P to find the grade according to percentage using if_else ladder.
    #find the gread according to percentage using if_else 
    #60 second
    #80 first
    #90 distiction
import math
#a=int(input("sub 1 mark:---"))
#b=int(input("sub 2 mark:---"))
#c=int(input("sub 3 mark:---"))
#d=int(input("sub 4 mark:---"))
#e=int(input("sub 5 mark:---"))
#f=int(input("sub 6 mark:---"))
#g=int(input("sub 7 mark:---"))
a=60
b=70
c=90
d=99
e=98
f=96
g=99

h=(a+b+c+d+e+f+g)
print(h)
i=(h/700)*100
print(i)

if h > 90 :
   print("distiction")
elif h >80:
   print("first class")
elif h > 60:
   print("second class")
elif h > 40:
   print("pass")
else:
   print("fail")
