# Find the maximum of a list of numbers
## Aim:
To write a program to find the maximum of a list of numbers.
## Equipment’s required:
1.  Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.	Get the list of marks as input
2.	Use the sort() function or max() function or use the for loop to find the maximum mark.
3.	Return the maximum value
## Program:

i)	# To find the maximum of marks using the list method sort.
```
''' 
Program to mark the maximum of marks using the list method sort
Developed by: S.Jaiganesh
RegisterNumber: 212222240037
'''
def max_marks(marks):
    marks.sort()
    return marks[-1]

```

ii)	# To find the maximum marks using the list method max().
```
''' 
Program to find the maximum marks using the list method max().
Developed by: S.Jaiganesh
RegisterNumber: 212222240037
'''
def max_marks(marks):
    return max(marks)

```

iii) # To find the maximum marks without using builtin functions.
```
''' 
Program to the maximum marks without using builtin functions.
Developed by: S.Jaiganesh
RegisterNumber: 212222240037
'''
def max_marks(list1):
    l=list1[0]
    for i in list1:
        if i>l:
            l=i
    return l        


```
## Sample Input and Output
![output](./img/max_marks1.jpg) 
![image](https://github.com/Jaiganesh235/FindMaximum/assets/118657189/a817b144-140e-4fc2-91a9-8962fc4ce867)


## Output:
i)	# To find the maximum of marks using the list method sort.
![image](https://github.com/Jaiganesh235/FindMaximum/assets/118657189/377ee5b6-09a8-4d64-a864-9d4b78158c25)

ii)	# To find the maximum marks using the list method max().
![image](https://github.com/Jaiganesh235/FindMaximum/assets/118657189/9c3ff0e9-7104-4ffb-b906-50c2a775c2d7)

iii) # To find the maximum marks without using builtin functions.
![image](https://github.com/Jaiganesh235/FindMaximum/assets/118657189/0628c1d1-9e9d-4a48-b4a9-c2fdcae625ad)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
