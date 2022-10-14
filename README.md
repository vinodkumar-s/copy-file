# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1: First we need to open the required file from one file to another file.

### Step 2: Using key word "with" to open the required file.
 
### Step 3: Again using the with keyword to open the empty file.

### Step 4:  The empty file is open by using "w" which is used to write only.  

### Step 5:The for fuction is used to take the each line from the main file.
 
### Step 6:Write() is used to write the lines of main file to the empty file or do the directed file.

### step7: print the output.

 

## PROGRAM:
 Developed by: s.vinod kumar
 
register number: 22004903
``` python
with open("file.txt","r")as fp:
    x=fp.read()
with open("file1.txt","w") as fp1:
    fp1.write(x)
```
### OUTPUT:
![output](/output%20(2).png)
![output](/output2.png)
![output](/output1.png)


## RESULT:
Thus the program is written to copy the contents from one file to another file.