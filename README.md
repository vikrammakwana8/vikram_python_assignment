# vikram_python_assignment
 
  (1)How to the python code Structure work?
  The python compiler reads a python source code or instruction line by line.
 
 
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

#find that who can donet the blood using nested if


(8) Compatible Blood Type Donors

# If your blood type is:	     You can give to:	      You can receive from:
# O Positive	                 O+, A+, B+, AB+	      O+, O-
# A Positive	                 A+, AB+              	A+, A-, O+, O-
# B Positive	                 B+, AB+	              B+, B-, O+, O-
# AB Positive	                 AB+ Only	              All Blood Types
# O Negative	                 All Blood Types	      O-
# A Negative	                 A-, A+, AB-, AB+	      A-, O-
# B Negative	                 B-, B+, AB-, AB+	      B-, O-
# AB Negative	                 AB-, AB+             	AB-, A-, B-, O-
a=0
while a<5:
 a +=1
 action=input("enter donate or receive(d/r):---")
 blood_group =input("donoer blood group(a±,b±,ab±,o±):--- ")

 if blood_group == "a+" :
   if action=="d":
     print( blood_group  + " can donet blood to a+ and ab+")
   else:
     print( blood_group  + " can receive blood from	A+, A-, O+, O-")
 elif blood_group == "b+":
   if action =="d":
     print(blood_group + " can donet blood to b+ and ab+")
   else:
     print( blood_group  + " can receive blood from	B+, B-, O+, O-")

 elif blood_group == "o+":
   if action =="d": 
     print(blood_group + " can donet blood to o+ a+ b+ and ab+")
   else:
     print( blood_group  + " can receive blood from O+, O-")

 elif blood_group == "ab+":
   if action =="d":
     print(blood_group + " can donet blood to ab+")
   else:
     print( blood_group  + " can receive blood from all")

 elif blood_group == "a-":
   if action =="d":
     print(blood_group + " can donet blood to a+, a-,ab+ and ab-")
   else:
     print( blood_group  + " can receive blood from	A-, O-")

 elif blood_group == "b-":
   if action =="d":
     print(blood_group + " can donet blood to b+, b-,ab+ and ab-")
   else:
     print( blood_group  + " can receive blood from	B-, O-")

 elif blood_group == "ab-":
   if action =="d":
     print(blood_group  +" can donet blood to ab+ and ab-")
   else:
     print( blood_group  + " can receive blood from AB-, A-, B-, O-")
  
 elif blood_group == "o-":
   if action =="d":
     print(blood_group  +" can donet blood to everyone")
   else:
     print( blood_group  + " can receive blood from O-")
     
(9)W.A.P to skip the (Banana) from the list using Continue Statement List1 -(apple,banana,mango)
l=["apple","banana","mango"]
for i in l:
  if i=="banana":
     continue
  else:
    print(i)
    
 (10)#W.A.P to break the for loop when (Banana) get in if Condition.
 
l=["apple","banana","mango"]
for i in l:
  if i=="banana":
     break
  else:
    print(i)
    
  (11)W.A.P to print (Hello) using string 
print("Hello")


(12)W.A.P to allocate the string to a variable.

string = "Hello"


(13)W.A.P to print String using three quotes 
string='''hello !
            good morning '''
            
        
 (14) W.A.P to access the 1st position character using index value
string="good morning"
print(string[1])


(15)W.A.P to Access the string after the index value 1.
string="good morning"
print(string[2::])


(16) W.A.P to Access the string before the index value 5.
string="good morning"
print(string[:5:])


(17) W.A.P to Access the String between the index value 1 to 4 
string="good morning"
print(string[1:4:])


(18)W.A.P to print the string from the last index value.
string="good morning"
print(string[::-1])


(19)W.A.P to print the String alternate character after the index value 1.
string="good morning"
print(string[::2])
