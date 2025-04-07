# EX-NO-6-Pseudo-Random-Number

# AIM: 
Implementation of Pseudorandom Number Generation Using Standard library

# ALGORITHM:
1.Start the program and import the required libraries.

2.Seed the random number generator using the random.randint(min,max)

3.Get the number of randon number to generate.

4.Pass the value for number of iterations and print the numbers.

5.End the program.

# PROGRAM:

Name: Muthulakshmi D
Reg : 212223040122

```
import random


count = int(input("Enter the number of random numbers to generate: "))
min_val = int(input("Enter the minimum value: "))
max_val = int(input("Enter the maximum value: "))

print("Pseudorandom numbers:")
for _ in range(count):
    random_number = random.randint(min_val, max_val)
    print(random_number)
```
# OUTPUT:
![image](https://github.com/user-attachments/assets/90af1525-6a6d-4f90-956a-2ba5d615d6ba)

# RESULT:
The program for Pseudorandom Number Generation is executed successfully
