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
Program to mark the maximum of marks using the list method sort
Developed by: Karthick Raja K
RegisterNumber: 23006120
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
```

ii)	# To find the maximum marks using the list method max().
```Python
Developed by: Karthick Raja K
RegisterNumber: 23006120
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
```

iii) # To find the maximum marks without using builtin functions.
```Python
Developed by: Karthick Raja K
RegisterNumber: 23006120
def max_marks(list1):
    max1=list1[0]
    for i in list1:
        if i>max1:
            max1=i
    return max1

```
## Sample Input and Output
![output](./img/max_marks1.jpg) 
## Output:
![output](/Screenshot%202023-07-25%20203309.png)
![output](/Screenshot%202023-07-25%20203454.png)
![output](/Screenshot%202023-07-25%20203630.png)
## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.