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
Program to mark the maximum of marks using the list method sort
Developed by: N.Kishore
RegisterNumber: 212222240049
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
```

ii)	# To find the maximum marks using the list method max().
```
Program to find the maximum marks using the list method max().
Developed by: N.Kishore
RegisterNumber: 212222240049
def max_marks(marks):
    large=max(marks)
    return large
```

iii) # To find the maximum marks without using builtin functions.
```
Program to the maximum marks without using builtin functions.
Developed by: N.Kishore
RegisterNumber: 212222240049
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max= i
    return max
```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:

![Screenshot 2023-06-03 141601](https://github.com/nkishore2210/FindMaximum/assets/118707090/ac7a69dd-959a-4edd-b1a7-1ff98f73c527)

![Screenshot 2023-06-03 141636](https://github.com/nkishore2210/FindMaximum/assets/118707090/ec8d565a-d28d-4ba8-8f2a-297f9af301ce)

![Screenshot 2023-06-03 141703](https://github.com/nkishore2210/FindMaximum/assets/118707090/3216bb73-1886-4afd-9836-9240c2478017)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
