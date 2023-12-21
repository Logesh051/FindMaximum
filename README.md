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
''' 
Program to mark the maximum of marks using the list method sort
Developed by: Logesh.N.A
RegisterNumber: 23012242
'''
def max_marks(marks):
    marks.sort()
    large = marks[-1]
    return large

ii)	# To find the maximum marks using the list method max().
''' 
Program to find the maximum marks using the list method max().
Developed by: Logesh.N.A
RegisterNumber: 23012242
'''
def max_marks(marks):
    large = max(marks)
    return large

iii) # To find the maximum marks without using builtin functions.
''' 
Program to the maximum marks without using builtin functions.
Developed by: Logesh.N.A
RegisterNumber: 23012242
'''
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max        
## Output:
![Screenshot 2023-12-21 225552](https://github.com/Logesh051/FindMaximum/assets/144979188/91a07b44-de75-421e-b573-682aa9e28a49)
![Screenshot 2023-12-21 224800](https://github.com/Logesh051/FindMaximum/assets/144979188/6c7dbe21-56a9-493a-930f-9268f0c03c4f)
![Screenshot 2023-12-21 225243](https://github.com/Logesh051/FindMaximum/assets/144979188/2c821b54-b497-473f-ae12-58610236f3b2)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
