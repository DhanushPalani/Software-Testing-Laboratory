# Ex.No: 3 To check the number is prime or not and inspect for failures.
 
### DATE:                                                                            
### REGISTER NUMBER : 212222040034
### AIM: 
Write a python program to check the number is prime or not and inspect for failures.
 
### Algorithm:
1. Start the program.
2. Get the number to be checked from the user.
3. If the number is less than or equal to 1, return "Not Prime".
4. If the number is 2, return "Prime".
5. Start the iteration from 3, For each iteration:
6. If the number is divisible by the current iteration value, return "Not Prime".
7. If the number is not divisible by any value from 2 to the square root, return "Prime".
8. Stop the program.

### Program:
```
a=int(input("Enter the number:"))
if a>1:
	for i in range(2,a):
		if a%i==0:
			print("It is not prime number")
			break
	else:
		 print("It is a prime number")
else:
	print("It is not a prime number")
```



### Output:


![Screenshot 2024-09-27 110757](https://github.com/user-attachments/assets/d0487c2c-1eb0-4f80-946b-970fca74d0d5)



### Result:
Thus, the python program to check the number is prime or not is implemented and the output is verified successfully.
