# Python
Programming in Python
Write python program to print first letter of your name 
a) Example: Peter
               *      *
               *             *
               *              *
               *      *
               *
               *
               *
b) Print your name by using for loop

c) check the user name is palindrome or not


Solutions:

a)  
print("\n===== Printing G =======\n")
for i in range(8):
    if i==0:
        print("*   *   *   *   *")
    elif i==4:
        print("*      *   *   *")
    elif i==5 or i==6:
        print("*      *\t*")
    elif i==7:
        print("*  *   *\t*")
    else:    
        print('*')

print("\n=======================")


b)
string = "Gauraansh"

for char in string:
    print(char)


c)

name = input("Enter your name: ")

name = name.lower()
name = name.replace(" ", "")

if name == name[::-1]:
    print("Name is Palindrome")
else:
    print("Name is not Palindrome")
