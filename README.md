# Assignment2
This repository contains Python scripts for basic programming practice.  

## 📌 Task 1: Check if a Number is Even or Odd
### Problem Statement:  
Write a Python program that:  
1. 	Takes an integer input from the user.
2. 	Checks whether the number is even or odd using an if-else statement.
3. 	Displays the result accordingly.

### Code: 
a=int(input("Enter any number: "))
if a%2==0:
    print(a," is an Even number")
else:
    print(a,' is an Odd number')

### Example Output:  
Enter any number: 25
25  is an Odd number

## 📌 Task 2: Sum of Integers from 1 to 50 Using a Loop 
### Problem Statement:  
Write a Python program that:  
1.   Uses a for loop to iterate over numbers from 1 to 50.
2.   Calculates the sum of all integers in this range.
3.   Displays the final sum.

### Code: 
sum=0
for i in range(1,51):
    sum+=i
print("The sum of numbers from 1 to 50 is:", sum)

### Example Output:  
The sum of numbers from 1 to 50 is: 1275
