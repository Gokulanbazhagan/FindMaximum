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
Developed by: Gokularamanan k
RegisterNumber: 212222230040
'''
def max_marks(marks):
    marks.sort()
    large = marks[-1]
    return large


```

ii)	# To find the maximum marks using the list method max().
```

''' 
Program to mark the maximum of marks using the list method sort
Developed by: Gokularamanan k
RegisterNumber: 212222230040
'''
def max_marks(marks):
    marks.sort()
    large = marks[-1]
    return large

```

iii) # To find the maximum marks without using builtin functions.
```
''' 
Program to the maximum marks without using builtin functions.
Developed by:212222230040 
RegisterNumber: gokularamanan k
'''
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max



```
##  Output
i)	# To find the maximum of marks using the list method sort.
![max1](https://github.com/Gokulanbazhagan/FindMaximum/assets/119518996/d215267f-b255-4d7f-aa97-7eca000f7801)
ii)	# To find the maximum marks using the list method max().
![max2](https://github.com/Gokulanbazhagan/FindMaximum/assets/119518996/01109ba5-475f-4321-9516-7a61877972e4)

iii) # To find the maximum marks without using builtin functions.
![max3](https://github.com/Gokulanbazhagan/FindMaximum/assets/119518996/92b743b4-b368-4cd7-82d2-280ecf60aaf3)


 


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
