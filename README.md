# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7

ALGORITHM:

Step 1:
Create two empty files.

Step 2:
In one file.txt enter some content and save the file.

Step 3:
In other file1.txt file read the file.txt using .read() build in function.

Step 4:
Next open file1.txt in write mode.

Step 5:
Copy file.txt using copy() funtion.

Step 6:
Run the program.

## PROGRAM:
```
Developed by: K.NIVETHA

Reference Number:22009186

with open('f1.txt','r')as firstfile:
    with open('f2.txt','a')as secondfile:
        for line in firstfile:
            secondfile.write(line)


```            
### OUTPUT:

![cop](https://user-images.githubusercontent.com/119559844/215276227-67831a3b-6d25-44c3-b444-f2140fdbb83c.png)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
