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
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
```
ii)	# To find the maximum marks using the list method max().
```
def max_marks(marks):
    large=max(marks)
    return large
```
iii) # To find the maximum marks without using builtin functions.
```
def max_marks(list1):
    max_num=list1[0]
    for i in list1:
        if i>max_num:
            max_num=i
    return max_num
```
## Output:
![Screenshot 2024-03-31 145615](https://github.com/AnbuSelvanS7/FindMaximum/assets/151528411/04455395-de8b-40a8-b750-0c279df77612)
![Screenshot 2024-03-31 145632](https://github.com/AnbuSelvanS7/FindMaximum/assets/151528411/05350a66-cb6f-45f3-93c5-347c43536921)
![Screenshot 2024-03-31 145647](https://github.com/AnbuSelvanS7/FindMaximum/assets/151528411/f3d738ca-d3dd-44d2-a522-8e7b4e6c7935)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
