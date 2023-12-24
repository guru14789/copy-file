# copy-file
## AIM:
To write a Python program for copying the contents from one file to another file.
## EQUIPMENT REQUIRED: 
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
End of the program

## PROGRAM:
```
def copy_file(source_file_path, destination_file_path):
    with open(source_file_path, 'r') as source_file, open(destination_file_path, 'w') as destination_file:
        destination_file.write(source_file.read())
    print("copying done...")


source_path = 'C:\\Users\\admin\\OneDrive\\Desktop\\text.txt'  
destination_path = 'C:\\Users\\admin\\OneDrive\\Desktop\\destination.txt'
copy_file(source_path, destination_path)

```

### OUTPUT:
### python output:
![file1](https://github.com/guru14789/copy-file/assets/151705853/b71f9413-1dc5-41d2-92ea-51e4df5f3087)
### original text file:
![file2](https://github.com/guru14789/copy-file/assets/151705853/a7862743-bb14-469e-8212-98ee4d8d4f69)
### duplicate text file:
![file3](https://github.com/guru14789/copy-file/assets/151705853/82bd1b99-79c2-4bf1-8b2b-b99d513cbb6d)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
