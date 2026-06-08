# Exp.No:2d
## LOOPING PATTERNS - PRINTING PATTERN

---

### AIM  
To write a  python program  to print the downward pyramid pattern of stars


---

### ALGORITHM


1. **Start**
2. **Input** a number `a` from the user.
3. **Repeat** for `i` from `a` down to `1`:
   - Repeat for `j` from `1` to `i`:
     - Print `*` with a space (stay on the same line).
   - Move to the next line.
4. **End**



### PROGRAM
```
#Reg.No:212223060254
#Name:SENTHIL KANAGAVEL BALASUNDARAM
#Add Your Code Here
a=int(input())
for i in range(a,0,-1):
    for j in range(1,i+1):
        print("*",end=" ")
    print()    

```

### OUTPUT
![image](https://github.com/user-attachments/assets/f9bc9157-3130-4bc0-82de-fb2beeec688a)


### RESULT
thus the python program  to print the downward pyramid pattern of stars was executed successfully
