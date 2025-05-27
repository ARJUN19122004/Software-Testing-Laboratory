# Ex.No: 1 Write programs in Python Language to demonstrate the working of followingconstructs with possible test cases: a) do…while b) while…do c) if …else d) switch e) for 

### DATE:                                                                         
### REGISTER NUMBER : 212222040012

### AIM:  
To write python programs for do…while, while, for, switch and if…else and test with possible test 
Cases 

### Algorithm:
1. Start the program.
2. Create separate files for each given program.
3. Write simple program for each construct.
4.  the program with possible test cases.
5. Stop the program.
### Program:

### Do While:
```
def display():
    start=input("Enter a positive value for START: ")
    end=input("Enter a positive value for END: ")
    if start.isnumeric() and end.isnumeric():
        while True:
            start=int(start)
            end=int(end)
            print(start,end=' ')
            if start<end:
                start+=1
            else:
                break
    else:
        print("Enter a valid positive number.")
display()
```
### While Do:
```
start=input("Enter a positive value for START: ")
end=input("Enter a positive value for END: ")
if start.isnumeric() and end.isnumeric():
    start=int(start)
    end=int(end)
    while start<end:
        print(start)
        start+=1
else:
    print("Enter a valid positive number.")
```
### Switch:
```
def switch():
    switcher={0:"even",1:"odd"}
    n=input('Enter a value for N: ')
    try:
        n=int(n)
        print(switcher[n%2])
    except ValueError:
        print("Enter a valid number.")
switch()
```
### If Else:
```
def compare():
    a=input("Enter a value for A: ")
    b=input("Enter a value for B: ")
    try:
        a=int(a)
        b=int(b)
        if a>b:
            print("A is greater than")
        elif a<b:
            print("B is greater than")
        else:
            print("A is equal to B")
    except ValueError:
        print("Enter a valid number.")

compare()
```
### For:
```
def iterate():
    string=input("Enter a string: ") 
    for i in string:
        print(ord(i),end=" ")
iterate() 
```

### Output:

### Do While:
![image](https://github.com/user-attachments/assets/4b045458-e2a6-48b5-901f-b7114e9a98f4)


### While Do:
![image](https://github.com/user-attachments/assets/ad1891db-66ed-42b6-9ff4-c66d3851c1e8)


### Switch:
![image](https://github.com/user-attachments/assets/93a695cf-c950-40a6-b4a9-62bf2a20bcfd)


### If Else:
![image](https://github.com/user-attachments/assets/ff82867f-1260-485d-8ed0-0e4616cd990f)


### For:
![image](https://github.com/user-attachments/assets/ceea25f0-61ff-4271-b14b-6b8885baa9ce)





### Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.


