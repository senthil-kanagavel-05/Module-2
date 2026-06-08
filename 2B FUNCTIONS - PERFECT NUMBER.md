# Exp.No:2b  
## FUNCTIONS - MULTIPLICATION

### AIM  
To write a python program to define a function named "result" that accepts 3  values and return its  multiplication
---

### ALGORITHM

### Algorithm:

1. **Start**
2. **Input** three numbers: `a`, `b`, and `c`.
3. **Compare** the numbers:
   - If `a` is greater than or equal to `b` and `a` is greater than or equal to `c`, then `a` is the largest.
   - Else if `b` is greater than or equal to `a` and `b` is greater than or equal to `c`, then `b` is the largest.
   - Otherwise, `c` is the largest.
4. **Output** the largest number.
5. **End**



---

### PROGRAM
```
#Reg.No:212223060214
#Name:s pugazhendhi
#Add your Code Here
def result(a, b, c):
    multiplication_result = a * b * c
    return multiplication_result

a = int(input())
b = int(input())
c = int(input())

result_value = result(a, b, c)
print(f"Multiply is {result_value}")


```
### OUTPUT
![Screenshot 2025-04-30 114731](https://github.com/user-attachments/assets/ceec4f0c-6cf3-44ac-ae12-426b46ad568c)


### RESULT
thus the python program to define a function named "result" that accepts 3  values and return its  multiplication was executed successfully
