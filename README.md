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
# Developed By   : SANJAY M
# Register No    : 212223230187

def max_marks(marks):
    marks.sort()
    large = marks[-1]
    return large



```

ii)	# To find the maximum marks using the list method max().
```Python

# Developed By   : SANJAY M
# Register No    : 212223230187

def max_marks(marks):
    large = max(marks)
    return large



```

iii) # To find the maximum marks without using builtin functions.
```Python
# Developed By   : SANJAY M
# Register No    : 212223230187


def max_marks(list1):
    max = list1[0]
    for i in list1:
        if i>max:
            max = i
    return max


```



## Output:
![Screenshot 2024-04-02 173303](https://github.com/sanjayofficial2005/FindMaximum/assets/148048602/3b0a6aef-1824-433d-8e39-3f0937575e18)
![Screenshot 2024-04-02 172508](https://github.com/sanjayofficial2005/FindMaximum/assets/148048602/327ea493-d020-4efd-8cc5-e8981a9d38e6)
![Screenshot 2024-04-02 173345](https://github.com/sanjayofficial2005/FindMaximum/assets/148048602/e846d257-9efb-4132-9867-c5e32b542307)
![Screenshot 2024-04-02 172508](https://github.com/sanjayofficial2005/FindMaximum/assets/148048602/5e215b19-a612-4087-8fbe-23b1d420a5f3)
![Screenshot 2024-04-02 173413](https://github.com/sanjayofficial2005/FindMaximum/assets/148048602/2489ed57-3178-400f-9d46-048a733575a6)
![Screenshot 2024-04-02 172545](https://github.com/sanjayofficial2005/FindMaximum/assets/148048602/263c46e9-b473-42cb-b1ef-bd783d9bf22a)






## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
