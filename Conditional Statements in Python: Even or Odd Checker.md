# Conditional Statements in Python

## 🎯 Aim
To write a Python program to check whether the given number is **odd** and if it is **greater than 25** or **equal to 25** using ` nested if` statements.

## 🧠 Algorithm
1. Get an input from the user.
2. Convert the input to an integer and store it in a variable `a`.
3. Use the modulo operator `%` to check if `a % 2 == 0`.
   - If true, print `"a is a Odd number"`.
   - Else, print `"a is NOT an Odd number"`.
4. Use nested if to check whether a is greater or equal to 25 if it is odd. 
4. End the program.

## 🧾 Program
```
a=int(input())
if(a%2!=0):
    print(a,"is an Odd number")
    if(a<25):
        print(a,"is lesser than 25")
    else:
        print(a,"is greater than or equal to 25")
else:
    print(a,"is NOT an Odd number")
```
## Output
<img width="1017" height="843" alt="image" src="https://github.com/user-attachments/assets/3565356a-ca07-434e-a6e6-17c1a6c6b9f6" />

## Result
Thus,the given Python Program has been executed successfully.
