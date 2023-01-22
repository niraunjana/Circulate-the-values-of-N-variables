# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Get the n values from the user
### Step 2: 
Circulate the values of n variables
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
Print both the values it would be circulated
### Step 6: 
End the program
## Program:
```python
#Program to circulate N values.
#Developed by: NIRAUNJANA GAYATHRI G R
#RegisterNumber: 22008369
a=eval(input())
b=int(input())
def circulate():
    for n in range (b+1):
        c=a[n:]+a[:n]
    return c
print("After circulating the values are:",circulate())
```
## Output:
![WhatsApp Image 2023-01-22 at 15 47 52](https://user-images.githubusercontent.com/119395610/213910865-cac39147-f299-4487-b62e-44c39df3b257.jpg)
![WhatsApp Image 2023-01-22 at 15 48 08](https://user-images.githubusercontent.com/119395610/213910876-cbc115b6-e4f3-4662-9421-78bccedc47f2.jpg)



## Result:
Thus circulating the values of n variables are successfully executed
