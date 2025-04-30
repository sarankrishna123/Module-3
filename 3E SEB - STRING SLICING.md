# Exp.No:3e
## SEB - STRING SLICING

---

### AIM  
To write a Python function that accepts a string and forms a new string by reversing the characters from the **4th position to the 10th position** with **alternate characters**, and then prints the new string.

---

### ALGORITHM

1. Begin the program.  
2. Accept a string as input.  
3. Take a slice of the input string from index **2** to **10** (Python uses 0-based indexing, so index 2 refers to the 3rd character, i.e., the 4th character in natural terms).  
4. Reverse the sliced substring.  
5. Extract every second character from the reversed substring using slicing (`[::2]`).  
6. Print the final processed string.  
7. Terminate the program.

---

### PROGRAM

```
reg no:212223070023
name:Saran Krishna P S
def reverse_alternate_chars_substring(s):
    substring = s[3:10]
    reversed_alternate = substring[::-2]
    print(reversed_alternate)
reverse_alternate_chars_substring("abcdefghijklm")

```

### OUTPUT
![image](https://github.com/user-attachments/assets/d9f35c95-7dc5-4ba9-ae26-9896e3e4f804)

### RESULT
thus the above program is executed successfully.
