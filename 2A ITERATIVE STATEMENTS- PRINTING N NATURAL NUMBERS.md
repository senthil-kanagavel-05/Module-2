# Exp. No: 2a  
## ITERATIVE STATEMENTS – BINARY NUMBER PATTERN

###  Aim
To create a Python  program to print binary number pattern of n rows and m columns using loop

###  Algorithm

1. Start
2. Input the number of rows
3. Input the number of columns
4. Repeat the following steps for each row (from 1 to rows):
   - Repeat the following for each column (from 1 to columns):
     - Print `1` without moving to the next line
   - Move to the next line after printing all columns
5. End



### 🧾 Program

```python
#Reg.NO. 212223060254
#Name. SENTHIL KANAGAVEL BALASUNDARAM
#Write your Code here
def binary_pattern(rows, columns):
    for i in range(rows):
        for j in range(columns):
            print('1', end='')
        print()

# Taking input from the user
rows = int(input())
columns = int(input())

# Printing the binary pattern
binary_pattern(rows, columns)


```
### OUTPUT

![Screenshot 2025-04-30 114000](https://github.com/user-attachments/assets/abbe196a-c0da-4fb1-b48f-35408711b68d)



### RESULT
```
thus the  Python  program to print binary number pattern of n rows and m columns using loop was executed successfully

```

