# Exp.No:16  
## DICTIONARY - Create a Dictionary of Character Frequencies from a String

### AIM  
To write a Python program that takes a string input from the user and returns a dictionary where keys are characters and values are their respective frequencies.

### ALGORITHM

1.	Begin the program.
2.	Use input() to read a string from the user.
3.	Initialize an empty dictionary.
4.	Traverse each character in the string:
  •	If the character is already in the dictionary, increment its count.
  •	Otherwise, add the character with a count of 1.
5.	Display the resulting dictionary.
6.	Terminate the program.


### PROGRAM

```
#Reg.No:212222040120
#Name:PRASANNA R
#Add Your Code Here
def character_frequency(s):
    frequency = {}
    for char in s:
        if char in frequency:
            frequency[char] += 1
        else:
            frequency[char] = 1
    return frequency
user_input = input()
result = character_frequency(user_input)
print(result)

```

### OUTPUT

![LAB4 DAY1](https://github.com/user-attachments/assets/ae232599-1159-4763-a133-144c5f4b67c3)


### RESULT
Thus, the Python program to create a dictionary of character frequencies from a string has been implemented and executed successfully.
