# Find the maximum of a list of numbers
## Aim:
To write a program to find the maximum of a list of numbers.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.	Get the list of marks as input
2.	Use the sort() function or max() function or use the for loop to find the maximum mark.
3.	Return the maximum value
## Program:

i)	# To find the maximum of marks using the list method sort.
```Python
''' 
Program to mark the maximum of marks using the list method sort
Developed by: 
RegisterNumber: 
'''
def max_marks(marks):
    return max(marks)


```

ii)	# To find the maximum marks using the list method max().
```Python
def max_marks(marks):
    marks.sort()
    return marks[-1]


```

iii) # To find the maximum marks without using builtin functions.
```Python
def max_marks(list1):
    max=list1[0]
    for x in list1:
        if x>max:
            max=x
    return max


```
## Sample Input and Output
![max 1](https://user-images.githubusercontent.com/121215739/214829612-c2cf3a98-9839-4be1-8369-0b9987e1c754.png)
![max 2](https://user-images.githubusercontent.com/121215739/214829666-da685249-19a6-4faa-8267-ddabb4610afa.png)
![max 3](https://user-images.githubusercontent.com/121215739/214829703-668a42f2-c299-4901-9658-fa76f435c042.png)


## Output:
![max_output](https://user-images.githubusercontent.com/121215739/214829739-9faca193-8595-43bb-8102-c517f9f79842.png)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
