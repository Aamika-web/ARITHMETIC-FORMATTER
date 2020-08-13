def arithmetic_problems(problems):
    l = len(problems)
    for i in problems:
        x,y,z = i.split()
        x = int (x)
        z = int (z)

    if(len(problems) > 5):
        print("Error : Too many problems")
    elif(y!= '+' or y!= '-'):
        print("Error : Only addition and substraction")
    elif(x!= int or  z!= int):
        print("Error : must be digits only")
    elif(x or z >'5'):
        print("Error : must not exceed than four")
    else:
        print("x /n,y /n,z /n")
    return
