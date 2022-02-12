# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM:
Step 1:
Create a function that takes two inputs, an existing file name and a new file name.

Step 2:
Open the existing file in read mode.

Step 3:
Open the new file in write mode.

Step 4:
Read the contents on existing file using read() and store it in a variable.

Step 5:
Copy the variable data into the new file using write().

Step 6:
Call the function.

## PROGRAM:
'''
Python program for copying the contents from one file to another file.

Developed by: B.Paarkavy

RegisterNumber:21500424
'''

```
def copy(fname,newfile):
  with open(fname,'r')as fp:
    with open(newfile,'w')as fp1:
      data1=fp.read()
      fp1.write(data1)
fname=input("Enter an existing file: ")
newfile=input("Enter a name for new file: ")
copy(fname,newfile)
```

### OUTPUT:
New Text File "File3.txt":
![copy2](https://user-images.githubusercontent.com/93509383/153723177-207c3685-afd0-4ec4-a116-af5c5d8c51c2.jpeg)


Output of the code(to receive input):
![copy1](https://user-images.githubusercontent.com/93509383/153723179-f216209f-4f48-4b94-b874-53149fe7e282.jpeg)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
