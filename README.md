# copy-file

## AIM:
To write a python program for copying the contents from one file to another file.

## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7

## ALGORITHM:

### Step 1:
Create a text1.txt with some content in it.

### Step 2: 
Open the text1.txt file in read mode.

### Step 3: 
Create a copy.txt file using write mode.

### Step 4:  
Copy the content of text1.txt file to copy.txt using write function.

## PROGRAM:
```
Program for copying the contents from one file to another file
Developed by: Surendhar A
RegisterNumber: 212222110049

with open("text1.txt",'r') as fp:
    msg1=fp.read()
with open("copytxt",'w') as fp1:
    fp1.write(msg1)
```

### OUTPUT:
![5c1](https://github.com/Surendhar6/copy-file/assets/118352907/770468f9-8a50-4be6-8250-ee89082f69e4)
![5c2](https://github.com/Surendhar6/copy-file/assets/118352907/9ca7980d-5647-4422-bbe6-81d17e06cbe3)
![5c3](https://github.com/Surendhar6/copy-file/assets/118352907/10fd233d-c199-4254-92e7-5c26a4b18d8a)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
