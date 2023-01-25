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
Developed by: SARGURU K
RegisterNumber: 22002828


def max_marks(marks):
    marks.sort()
    large = marks[-1]
    return large
max_marks([0,60,80,30,76,23])



```

ii)	# To find the maximum marks using the list method max().
```
Developed by: SARGURU K
RegisterNumber: 22002828

def max_marks(list1):
    maxi = list1[0]
    for i in list1:
        if i>maxi:
            maxi=i
    return maxi



```

iii) # To find the maximum marks without using builtin functions.
```
Program to the maximum marks without using builtin functions.
Developed by:SARGURU
RegisterNumber: 22002828


def max_marks(marks):
    maxi=max(marks)
    return maxi



```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
### For Program 1
![1](https://user-images.githubusercontent.com/118704873/214075630-40e7c792-4c61-4ce4-9c47-f44820a1f9bf.png)

### For Program 2
![2](https://user-images.githubusercontent.com/118704873/214075687-98ebc22e-efb4-4e96-9146-0f49846608ba.png)

### For Program 3
![3](https://user-images.githubusercontent.com/118704873/214075732-3bfaaa5b-573f-404e-82ba-7fcd70624824.png)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
