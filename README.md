ser = "nobwendel"

password = "perez"

x = 1

while x == 1:

    a = input("Username: ")
    b = input("password: ")

    if user == a and password != b:
        print ("password incorrect")
        x += 0
    elif user != a and password ==b:
         print("Username incorrect")
         x += 0
    elif user == a and password == b:
        print("Username and Password correct")
        break
    else:
         print("Username and Password Incorrect")
         x += 0
