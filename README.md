# Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Get the file name and location from the user.

### Step 2:
Give a new file name to create a copy of a file content.

### Step 3:
Read the file and close the file.

### Step 4:
Now write the content in the new file.

### Step 5:
When done print"File copied successfully".

### Step 6:
End program.
## PROGRAM:
~~~
#To write a python program for reading content from a CSV file.
#Developed by: PRASANTH E
#Register Number: 212221233002
with open("text1.txt",'r') as fp:
    msg1=fp.read()
with open("copy.txt",'w') as fp1:
    fp1.write(msg1)

~~~
### OUTPUT:
![image](https://github.com/ganesh10082006/Copy-File/assets/151981672/ae1900a9-09c6-4b5e-925e-22b5f0ded586)

![image](https://github.com/ganesh10082006/Copy-File/assets/151981672/7f51b3f9-fb65-484c-85e3-06fc71577433)

![image](https://github.com/ganesh10082006/Copy-File/assets/151981672/d7ff52a5-e588-4abb-99b3-d15ab9ca5d1a)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
