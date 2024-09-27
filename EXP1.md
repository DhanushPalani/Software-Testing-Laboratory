# Ex.No: 1 Write programs in Python Language to demonstrate the working of followingconstructs with possible test cases: a) do…while b) while…do c) if …else d) switch e) for 

### DATE:                                                                            
### REGISTER NUMBER : 212222040034

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

## Do...While:
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
## While..do
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
## If...else
```
def compare(): 
	a=input("Enter a value for A: ") 
	b=input("Enter a value for B: ") 
	try: 
		a=int(a) 
		b=int(b) 
		if a>b: 
			print("A is greater than B") 
		elif a<b: 
			print("B is greater than A") 
		else: 
			print("A is equal to B") 
	except ValueError: 
		print("Enter a valid number.")
compare()
```
## Switch
```
def switch(): 
	switcher={ 0:"even", 1:"odd" } 
	n=input('Enter a value for N: ') 
	try: 
		n=int(n) 
		print(switcher[n%2]) 
	except ValueError: 
		print("Enter a valid number.") 
switch() 
```
## For
```
def iterate(): 
	string=input("Enter a string: ") 
	for i in string: 
			print(ord(i),end=" ") 
iterate() 
```












### Output:
## Do..while
![Screenshot 2024-08-23 113319](https://github.com/user-attachments/assets/9f70e407-b4a1-40ad-9943-b0086fc9fd4c)
## While..do
![Screenshot 2024-08-23 113334](https://github.com/user-attachments/assets/8446557e-1193-48b0-8fec-bdf77b628056)
##  If..else
![Screenshot 2024-08-23 113358](https://github.com/user-attachments/assets/5f2a81b0-c188-4423-8a50-6c9b654aeac3)
## Switch
![Screenshot 2024-08-23 113342](https://github.com/user-attachments/assets/b3e0f579-a2c3-465d-beae-cf9ee272d65c)
## For
![Screenshot 2024-08-23 113411](https://github.com/user-attachments/assets/acb1e794-570d-47a7-8681-42acbbeff8ab)






### Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.


