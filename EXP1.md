# Ex.No: 1 Write programs in Python Language to demonstrate the working of followingconstructs with possible test cases: a) do…while b) while…do c) if …else d) switch e) for 

### DATE:12.03.2025                                                                       
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

![Screenshot 2025-05-27 202012](https://github.com/user-attachments/assets/7258b32f-6caf-4fba-a631-f73b9581fa0c)


### While Do:
![Screenshot 2025-05-27 202325](https://github.com/user-attachments/assets/6773e347-1c14-40f6-a716-0ed13a3354ad)

### Switch:
![Screenshot 2025-05-27 202446](https://github.com/user-attachments/assets/7f22a4ea-4f12-47bb-a096-70b5bd2d14d9)


### If Else:
![![Screenshot 2025-05-27 202555](https://github.com/user-attachments/assets/b30ecd81-d27f-43ab-86f2-6533d98bbbae)


### For:

![Screenshot 2025-05-27 202641](https://github.com/user-attachments/assets/557d9166-8b93-447b-8ea1-305f3c950060)




### Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.


