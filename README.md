# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
First we need to open the required file form which we need to copy the text.

### Step 2: 
Using keyword "with" to open the requied file.
 
### Step 3: 
Again using the with keyword to open the empty file.

### Step 4:  
The empty file is open by using 'W' which is used to write only.

### Step 5: 
The four function is used to take each line from the main file.

### Step 6: 
write() is used to write the lines of main file to the empty file or to the directed file

## PROGRAM:
``` python
#python program for copying a file
#developed by:vinushcv
#registration number:22001897
with open("ok.txt","r") as fp:
    data=fp.read()
with open("copy.txt","w") as cp:
    cp.write(data)
```

### OUTPUT:
![output](copy%20file%20code.png)
![output](okcopy.png)
![output](copycopy.png)



## RESULT:
Thus the program is written to copy the contents from one file to another file.