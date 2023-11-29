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
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large


```

ii)	# To find the maximum marks using the list method max().
```Python
def max_marks(marks):
    large=max(marks)
    return large


```

iii) # To find the maximum marks without using builtin functions.
```Python
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max        


```


## Output:
![image](https://github.com/thenmozhi05/FindMaximum/assets/140684207/6f28b38a-9366-4619-927a-cc409b794a33)
![image](https://github.com/thenmozhi05/FindMaximum/assets/140684207/48503542-2904-4be4-aa16-4f6caad45199)
![image](https://github.com/thenmozhi05/FindMaximum/assets/140684207/b4af369c-0e55-46cd-be2b-50064a24c331)



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
