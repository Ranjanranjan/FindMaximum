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
Developed by: Ranjan k
RegisterNumber: 212222230116
'''
def max_marks(marks):
    a=sorted(marks)
    b=a[-1]
    return b


```

ii)	# To find the maximum marks using the list method max().
```Python

''' 
Program to find the maximum marks using the list method max().
Developed by: Ranjan K
RegisterNumber: 212222230116
'''
def max_marks(marks):
    a=max(marks)
    return a

```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: Ranjan K
RegisterNumber: 212222230116
'''
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max


```
## Sample Input and Output
![Screenshot 2023-11-07 083304](https://github.com/Ranjanranjan/FindMaximum/assets/130027697/e86b3022-0418-4ea8-a5a2-893c63d3c8a9)


## Output:
![Screenshot 2023-11-07 083007](https://github.com/Ranjanranjan/FindMaximum/assets/130027697/9c88f235-6a81-4c12-ad5f-d2ce838a0e56)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
