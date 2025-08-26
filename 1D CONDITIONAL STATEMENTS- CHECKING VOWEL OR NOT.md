## Experiment No: 1d – Conditional Statements- Checking Vowel or not

## AIM  
To Write a Python program to check whether the given character is a vowel or not using if..else statement
## ALGORITHM  
1. Begin the program.  
2. Take a character input from the user
3. Convert the character to lowercase
4. Check if the lowercase character is one of the vowels: 'a', 'e', 'i', 'o', 'u'
5. If it is a vowel, display "The given character is a vowel"
6. Otherwise, display "The given character is NOT a vowel"
4. Terminate the program.

## PROGRAM
```python
# Reg.No-212223060109
# Name-kamali R
# Write your code here

char = input("Enter a character: ")
char_lower = char.lower()

if char_lower in ['a', 'e', 'i', 'o', 'u']:
    print("The given character is a vowel")
else:
    print("The given character is NOT a vowel")
```

## OUTPUT
<img width="988" height="216" alt="image" src="https://github.com/user-attachments/assets/ef9137d2-dd4b-4ff2-8e3b-7c0abd134eb8" />

## RESULT
Thus the Python program to check whether the given character is a vowel or not using if..else statement is executed successfully.
