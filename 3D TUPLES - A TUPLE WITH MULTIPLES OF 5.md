# Exp.No:3d  
## TUPLES - A TUPLE WITH MULTIPLES OF 5

---

### AIM  
To write a Python program to create a tuple containing all multiples of 5 up to a given number **N**.

---

### ALGORITHM

1. Begin the program.  
2. Accept an integer `N` from the user.  
3. Use a generator expression inside the `tuple()` function to create a tuple `multiples_of_5` with values starting from `5` up to `N - 1`, stepping by `5`.  
4. Return the tuple `multiples_of_5`.  
5. Print the resulting tuple.  
6. Terminate the program.

---

### PROGRAM

```
reg no:212223070023
name:Saran Krishna P S
def multiples_of_5_up_to(N):
    return tuple(i for i in range(5, N + 1, 5))

N = int(input())
result = multiples_of_5_up_to(N)
print(result)

```

### OUTPUT
![image](https://github.com/user-attachments/assets/d8afee79-1ed5-42b1-bcc7-4eabad2b87e8)

### RESULT
thus the above program is executed successfully.
