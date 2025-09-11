# Exp.No:20  
## SEB -  Multiplication and Floor Division Using Class and if-elif


---

### AIM  
To create a Python program using a class named CSE with functions setvalues, mul, and div, and use user choices to perform multiplication, floor division, or exit.


---

### ALGORITHM

1.	Begin the program.
2.	Define a class CSE.
3.	Inside the class, define:
   o	setvalues(a, b) to assign values to instance variables.
   o	mul() to perform multiplication.
   o	div() to perform floor division.
4.	Create an object of the class.
5.	Accept two numbers and a choice from the user.
6.	Use if-elif-else to execute based on choice:
   o	Choice 1: Call mul()
   o	Choice 2: Call div()
   o	Choice 0: Print "Exiting!"
   o	Other: Print "Invalid choice"
7.	Terminate the program.

---

### PROGRAM

```
#Reg.NO:212222040120
#Name:PRASANNA R
class cse:
    def __init__(self,a,b):
        self.a=a
        self.b=b
    def mul(self):
        return self.a*self.b
    def div(self):
        return self.a//self.b
a=int(input())
b=int(input())
obj=cse(a,b)
choice=1
while choice!=0:
    choice=int(input())
    if choice==1:
        print("Result: ",obj.mul())
    elif choice==2:
        print("Result: ",obj.div())
    elif choice==0:
        print("Exiting!")
    else:
        print("Invalid choice!")


```

### OUTPUT

![image](https://github.com/user-attachments/assets/22fd91ec-8374-4ca1-9c95-bb17b0f159ea)


### RESULT
Thus, the Python program using class CSE to perform multiplication and floor division has been implemented and executed successfully.
