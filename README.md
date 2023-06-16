# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open the file f1 in read mode.

### Step 2:
Open the file f2 in append mode.

### Step 3:
Copy the contents using write() with the for loop.

### Step 4:
End the program.

## PROGRAM:
#Developed By: CHAITANYA PS
#Register No: 212222230024
with open('f1.txt','r') as f1:
    with open ('f2.txt','a') as f2:
        for line in f1:
            f2.write(line)

### OUTPUT:
![image](https://github.com/chaitanya18c/copy-file/assets/119392724/2c9ef20e-0efa-4dbc-911a-a4679e142fa5)
![image](https://github.com/chaitanya18c/copy-file/assets/119392724/2058cc71-9e40-4ae1-aca3-bb28101aaa28)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
