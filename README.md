# Module-5-Lab-Activity-

# PROBLEM 1.

i = 0  
print("Hello World")    
while (i <= 100):    
    print("Hello World")
    i = i + 1   


# PROBLEM 2.

numbers=[12,10,32,3,66,17,42,99,20]
#PART A
print("---Part A---")
for i in numbers:
    print(i)
print("---Part B---")
#PART B
for i in numbers:
    print(i," : ",i*i)

# PROBLEM 3.

import turtle
 
t = turtle.Turtle()
t.fillcolor('red')
t.begin_fill()
for i in range(5):
   t.forward(100) 
   t.right(72) 
t.fillcolor('red')
t.end_fill()


# PROBLEM 4.

for i in range(1,51):
    if(i%3==0 and i%5==0):
        print(str(i)+" is Divisible by both three and five")
    elif(i%5==0):
        print(str(i)+" is Divisible by five")
    elif(i%3==0):
        print(str(i)+" is Divisble by three")
    else:
        print("",end="")

# PROBLEM 5.

g = 200

for i in range(200):
  t.forward(g)
  t.right(200)
