# Exp.No:17  
## EXCEPTION HANDLING - INDEX ERROR

---

### AIM  
To accept a list of elements from the user and display a specific index; if the index is out of range, print a custom message using exception handling.


### ALGORITHM

1.	Begin the program.
2.	Accept the number of elements from the user.
3.	Create an empty list and use a loop to take input for list elements.
4.	Display the list.
5.	Use a try-except block to print the element at index 6.
6.	In case of an IndexError, print "6 is not accepted".
7.	Terminate the program.


### PROGRAM

```
Reg.No:212222040120
Name:PRASANNA R
Add Your Code Here
try:
    n = int(input())
    a = []
    for i in range(n):
        element = int(input())
        a.append(element)
    print(a)
    print(a[6])

except IndexError:
    print("6 is not accepted")
```

### OUTPUT

![LAB4 DAY2](https://github.com/user-attachments/assets/e2cb6462-1560-47db-8daf-b81c9c824e69)

### RESULT
Thus, the Python program to handle IndexError using exception handling has been implemented and executed successfully.
