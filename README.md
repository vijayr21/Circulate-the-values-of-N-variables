# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Get the two values from the user
### Step 2: 
Assign the value of second variable to a temporary variable
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
Print both the values it would be interchanged

### Step 6: 
End the program

## Program:
```
#Program to circulate N values.
#Developed by: VIJAY R
#RegisterNumber:23013759
def circulate():
    l=eval(input())
    n=int(input())
    l=l[n:]+l[:n]
    print("After circulating the values are:",l)
```

## Output:
![Screenshot 2023-12-01 000116](https://github.com/vijayr21/Circulate-the-values-of-N-variables/assets/149347607/6e714dec-a724-4470-81f9-b3a5e3b81337)

## Result:
Thus the Circulate n variables are successfully executed
## Result:
