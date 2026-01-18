 Task 1: Check if a Number is Even or Odd
Problem Statement:  Write a Python program that:
1. 	Takes an integer input from the user.
2. 	Checks whether the number is even or odd using an if-else statement.
3. 	Displays the result accordingly.

code:
a = int(input("Enter the first number: "))

if a % 2 == 0:
    print("The number is even.")
else:
    print("The number is odd.")

Output; When no, is even
Enter the first number: 2
The number is even.

When no. is odd
Enter the first number: 1
The number is odd.



Task 2 Sum of Integers from 1 to 50 Using a Loop
Problem Statement: Write a Python program that:
1.   Uses a for loop to iterate over numbers from 1 to 50.
2.   Calculates the sum of all integers in this range.
3.   Displays the final sum.

Code:
total = 0
for i in range(1, 51):
    total = total + i

print(f"The sum of numbers from 1 to 50 is: {total}")

Output:
The sum of numbers from 1 to 50 is: 1275
