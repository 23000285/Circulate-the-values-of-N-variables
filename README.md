# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Create a user defined function.
### Step 2: 
Get the variables from user to enter inside the list
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
After rotating the variables, store the rotated variables in a seperate list
### Step 6: 
At last, print the list of rotated variables
## Program:
```
#Program to circulate N values.
#Developed by: VENKATANATHAN P R
#RegisterNumber: 23000285
def circulate():
    l=eval(input())
    n=int(input())
    out=l[n:]+l[:n]
    print("After circulating the values are:",out)
```

## Output:
![image](https://github.com/23000285/Circulate-the-values-of-N-variables/assets/138970859/9898d002-3b96-4e26-b2fc-e1aee770f7a9)

## Result:
Thus the python program to circulate the n variable using function concept is successfully executed.
