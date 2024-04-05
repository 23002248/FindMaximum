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
```
#Program Developed by: STEPHEN RAJ.Y
#Register No:212223230217

def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large



```

ii)	# To find the maximum marks using the list method max().
```Python
#Program developed by: STEPHEN RAJ.Y
#Register No: 212223230217

def max_marks(marks):
    large=max(marks)
    return large



```

iii) # To find the maximum marks without using builtin functions.
```Python
#Program developed by: STEPHEN RAJ.Y
#Register No: 212223230217

def max_marks(marks):
    max_mark=0
    for i in marks:
        if i>max_mark:
            max_mark=i
    return max_mark



```



## Output:
i) # To find the maximum of marks using the list method sort.
![Screenshot 2024-04-05 145316](https://github.com/23002248/FindMaximum/assets/151701774/e75f9047-bcd5-4e9e-8f73-c22243f8feaf)

ii) # To find the maximum marks using the list method max().
![Screenshot 2024-04-05 145657](https://github.com/23002248/FindMaximum/assets/151701774/c97670d0-09dc-4ac7-9894-afb1b044217c)
iii) # To find the maximum marks without using builtin functions.
![Screenshot 2024-04-05 145802](https://github.com/23002248/FindMaximum/assets/151701774/61b18a08-51ca-4d6b-9060-2ad78debb6ad)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
