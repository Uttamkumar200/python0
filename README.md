# python0
a = int(input("enter the first no:")) 
b = int(input("enter the second no:")) 
c = int(input("enter the third no:")) 

if(a > b and a > c):
    print("a is greater")
elif(b > a and b > c):
    print("b is greater") 
else:
    print("c is greater")     


num = int(input("enter the no:"))
rem = num % 2
if(rem == 0):
    print("even")
else:
    print("odd")          
