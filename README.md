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

## Output:

![Screenshot 2023-06-03 141947](https://github.com/nkishore2210/FindMaximum/assets/118707090/191369e4-1322-4f4a-8217-b05d920c9416)

![Screenshot 2023-06-03 142017](https://github.com/nkishore2210/FindMaximum/assets/118707090/fd6e638e-619b-4d01-a48a-f2a681752771)

![Screenshot 2023-06-03 142042](https://github.com/nkishore2210/FindMaximum/assets/118707090/63e993e7-2760-4e7d-9c9e-b8a49d9a0423)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
