# Exp.No:2c
## BUILT-IN FUNCTIONS AND LAMBDA FUNCTIONS - RELATING TWO NUMBERS

### AIM  
To write a Python program to check the relation between two numbers —  quotient and remainder of the division on the given numbers — using a lambda function.

### ALGORITHM
1.Start
2.Accept or assign two numbers (say a and b).
3.Create a lambda function to compute:
Quotient → quotient = lambda a, b: a // b
Remainder → remainder = lambda a, b: a % b
4.Call both lambda functions with inputs a and b.
5.Display the results for:
Quotient
Remainder
6.End

### PROGRAM
x=int(input())
y=int(input())
z=lambda x,y:divmod(x,y)
print(z(x,y))

### OUTPUT
![image](https://github.com/user-attachments/assets/cabe0143-f269-4a75-a15b-a7090c008640)

### RESULT
Thus,Python program to check the relation between two numbers —  quotient and remainder of the division on the given numbers — using a lambda function was implemented and successfully executed.

