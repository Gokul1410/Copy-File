# Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
## Step 1:
Get the file name and location from the user.

## Step 2:
Give a new file name to create a copy of a file content.

## Step 3:
Read the file and close the file.

## Step 4:
Now write the content in the new file.

## Step 5:
When done print"File copied successfully".

## Step 6:
End of the program

## PROGRAM:

```
#Developed by: GOKUL C
#Register Number: 212223240040

def copy(fname,newfile):
    with open(fname) as fp:
        with open (newfile,'w') as fp1:
            data=fp.read()
            fp1.write(data)
copy("file1.txt","file2.txt")
```

### OUTPUT:

![331247291-a9b572af-2746-4e61-a62a-50205be150ca](https://github.com/Gokul1410/Copy-File/assets/153058321/cb421a95-6219-413e-8186-c072a9beeeda)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
