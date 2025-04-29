
## FILES -  COUNT NUMBER OF WORDS 

### AIM  

To write a Python program to read a file and count the number of words in it.

### ALGORITHM

1. Begin the program.  
2. Function create_file:
   Take file_path and file_content as input.
   Open the file in write mode ("w") and write the content to it.
3. Function count_words_in_file:
   Open the file in read mode ("r").
   Read the file content and split it into words.
   Return the count of words.  
4. Terminate the program.

### PROGRAM

```

def create_file(file_path, file_content):
    with open(file_path,"w") as file:
        file.write(file_content)

def count_words_in_file(file_path):
    with open(file_path,"r") as file:
        text=file.read()
        words=text.split()
        return len(words)

```

### OUTPUT

![image](https://github.com/user-attachments/assets/32a1cdc5-86d9-49af-b229-99a46ae991f1)

### RESULT

Thus the Python program to read a file and count the number of words in it was successfully created.
