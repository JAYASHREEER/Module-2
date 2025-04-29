# Exp.No:2d
## LOOPING PATTERNS - PRINTING PATTERN

### AIM  
To write a Python Program to print reversed pyramid pattern in Python and get the input for no of rows.

### ALGORITHM
1.Start
2.Read the number of rows n from the user.
3.Use a for loop with a variable i starting from n down to 1:
In each iteration:
Print (n - i) spaces.
Print (2 * i - 1) asterisks *.
4.Continue this until i = 1.
5.End

### PROGRAM
n=int(input())
j=n+1
space = (n-1)*2
for i in range(j,0,-1):
    print(space*" ",end="")
    for j in range(-1,n-i):
        print(end=" ")
    for j in range(0,i):
        print("*",end=" ")
    print()

### OUTPUT
![image](https://github.com/user-attachments/assets/82922dab-492c-4b73-a27a-1351ef91f857)

### RESULT
Thus, Python Program to print reversed pyramid pattern in Python and get the input for no of rows was implemented and successfully implemented.

