# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a file.
### Step 2: 
Write some lines in that file. 
### Step 3: 
Create a python file.
### Step 4:  
Write a code to copy the content of the file to a new file.
### Step 5: 
Run the program.
### Step 6: 
Display the output.
## PROGRAM:
```
Developed By:SHARMITHA V
Register No: 212223110048

def copy(filename,newfile):
    with open(filename,'r') as fp:
        with open(newfile,'w') as fp1:
            data1=fp.read()
            fp1.write(data1)
filename=input("Enter an Existing File:")
newfile=input("Enter a name for new file:")
copy(filename,newfile)
```

### OUTPUT:
![image](https://github.com/sharmitha3/copy-file/assets/145974496/8a57cd2c-58d1-43e8-aff2-978c90104b75)

![image](https://github.com/sharmitha3/copy-file/assets/145974496/71b814f4-718f-40a2-97ab-6e110403ea9a)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
