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
    marks.sort()
    max=marks[-1]
    return max


```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: praveen v
RegisterNumber: 23013808
'''
def max_marks(marks):
    max_marks=max(marks)
    return max_marks



```

iii) # To find the maximum marks without using builtin functions.
```Python

''' 
Program to the maximum marks without using builtin functions.
Developed by: 
RegisterNumber: 
'''
def max_marks(list1):
    maximum=list1[0]
    for i in list1:
        if i>maximum:
            maximum=i
    return maximum    


```
## Sample Input and Output


## Output:
![Screenshot 2023-11-16 213021](https://github.com/praveenv23013808/FindMaximum/assets/145824728/81a7edba-91fd-496b-8e39-552e03671639)
![Screenshot 2023-11-16 213408](https://github.com/praveenv23013808/FindMaximum/assets/145824728/8e457ad4-8c19-4439-a757-62fa96b1dbd8)
![Screenshot 2023-11-16 213500](https://github.com/praveenv23013808/FindMaximum/assets/145824728/a7163044-24c4-42a5-9524-59d1b0001911)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
