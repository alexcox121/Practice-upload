# Practice-upload
# Program To Make Simple Calculator
# This function adds 2numbers  #wrong comment
def add( x, y ):  # too many spaces
    return x + y  #no brackets

#This function subtracts  2numbers
def subtract(x, y):
    return x - y  #no brackets



       #This function multipliers 2numbers  #too many break lines and wrong indentation
def multiply(x, y):  
   return x * y  #wrong indentation, needs to be four spaces

##This function divides  2numbers    #incorrect comment with two hastag
def divide(x, y):
   return x / y       #wrong indentation, needs to be four spaces

print ( "Select operation.")    #too many spaces on each of the prints
print ( "1.Add")
print ( "2.Subtract")
print ( "3.Multiply")
print ( "4.Divide")

while True:        #should only be one line break 
   
   choice = input  ("Enter choice(1/2/3/4): ")# Take input from the  user   #comment should be on a separate line

   # Check if choice is 1 of the four options by completing the following code in the IDE of your choice or notebook
#comment is too long
   if choice in ('1', '2', '3', '4'):
        
      Num1   = float(input("Enter first number: "))    #incorrect spacing and colons
      Num2   = float(input("Enter second number: "))

       if CHOICE == '1':
           print(Num1, "+", Num2, "=", add( Num1, Num2 ))     #incorrect indentation 

       elif CHOICE == '2':
           print (Num1, "-", Num2, "=", subtract( Num1, Num2 ))

       elif CHOICE == '3':
           print (Num1, "*", Num2, "=", multiply( Num1, Num2 ))

       elif CHOICE == '4':
           print (Num1, "/", Num2, "=", divide( Num1, Num2 ))
       break
   else:

       Print( "Invalid Input" )#this prints the invalid input....
        
        
#Peer review to correctly write code
#This function is to add 2 numbers
def add(x, y):  
    return (x + y)  

#This function subtracts 2 numbers
def subtract(x, y):
    return (x - y) 

#This function multiplies 2 numbers  
def multiply(x, y):  
    return (x * y)  

#This function divides 2 numbers    
def divide(x, y):
    return (x / y)    

#print the operators
print("Select operation")   
print("1.Add")
print("2.Subtract")
print("3.Multiply")
print("4.Divide")

#Take input from the user
while True:
    choice = input  ("Enter choice(1/2/3/4): ")

# Check if choice is 1 of the four options by completing the following code in the IDE of your choice or notebook
if choice in ('1', '2', '3', '4'):
    Num1 = float(input("Enter first number: "))    
    Num2 = float(input("Enter second number: "))

if CHOICE == '1':
    print(Num1, "+", Num2, "=", add( Num1, Num2 ))     #incorrect indentation 

elif CHOICE == '2':
    print (Num1, "-", Num2, "=", subtract( Num1, Num2 ))

elif CHOICE == '3':
    print (Num1, "*", Num2, "=", multiply( Num1, Num2 ))

elif CHOICE == '4':
    print (Num1, "/", Num2, "=", divide( Num1, Num2 ))

break
    else:
        
    Print( "Invalid Input" )#this prints the invalid input....
