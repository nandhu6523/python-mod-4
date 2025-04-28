 
## EXCEPTION HANDLING

### AIM  

To create a Python program Placing msg as "You're out of list range" to avoid IndexError.

### ALGORITHM

1. Begin the program.  
2. Try to raise an IndexError with a custom message.
3. Catch the IndexError exception using except.
4. Print the message "You're out of list range" if the exception is raised.
5. Terminate the program.

### PROGRAM

```


try:
    raise IndexError("Trying to access an element out of list's range")

except IndexError:
    print("You're out of list range")

```

### OUTPUT

![image](https://github.com/user-attachments/assets/76d1fde2-ab2a-4c00-8948-3781d04e77fb)

### RESULT

Thus the  Python program Placing msg as "You're out of list range" to avoid IndexError was succcessfully created.
