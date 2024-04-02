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
def max_marks(marks):#we are passing the aruement
    marks.sort()#this just sorts the list in ascending order
    large=marks[-1]#the last value of the list gets assigned to the variable
    return large#returns the largest value
```

ii)	# To find the maximum marks using the list method max().
```
def max_marks(marks):#we are passing the aruement
    large=max(marks)#we are using max as a function rather than marks.max
    return large#returns the largest value
```

iii) # To find the maximum marks without using builtin functions.
```
# we must use loops
def max_marks(list1):
    max=list1[0]
    for i in list1:# given by sir
        if i>max:
            max=i
    return max
```



## Output:
![python exp 6 q1](https://github.com/SVENGADAKRISHNAN/FindMaximum/assets/147473084/5e32a984-8fa8-4f75-a500-45e3f126ff6a)

![python exp 6 q2](https://github.com/SVENGADAKRISHNAN/FindMaximum/assets/147473084/d6bce4e1-5b4a-4099-8ad0-9a08de38aa79)

![python exp 6 q3](https://github.com/SVENGADAKRISHNAN/FindMaximum/assets/147473084/c42b368f-6a0b-422d-8937-236f3202df6d)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
