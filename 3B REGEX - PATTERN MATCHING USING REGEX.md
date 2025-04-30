# Exp.No:3b  
## REGEX - PATTERN MATCHING USING REGEX

---

### AIM  
To write a Python program that matches a string containing an `'a'` followed by **two to three `'b'` characters** using regular expressions.

---

### ALGORITHM

1. Begin the program.  
2. Accept a string `str1` from the user.  
3. Define the regular expression pattern as `r"[a]+b{2,3}"`.  
4. Use the `re.match()` function to check if the string `str1` matches the pattern.  
5. If a match is found, print `"Found a match!"`.  
6. If no match is found, print `"Not matched!"`.  
7. Terminate the program.

---

### PROGRAM

```
reg no:212223070023
name:Saran Krishna P S
import re

pattern = r'ab{2,3}'
test_strings = ["ab", "abb", "abbb", "abbbb", "a", "b", "aabbb"]

for s in test_strings:
    if re.fullmatch(pattern, s):
        print(f"Matched: {s}")
    else:
        print(f"Not matched: {s}")

```
### OUTPUT
![image](https://github.com/user-attachments/assets/be3778c6-2472-40df-8588-c800b2ce4077)

### RESULT
Thus the above program is executed successfully.
