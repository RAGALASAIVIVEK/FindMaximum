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

i)'''Program to mark the maximum of marks using the list method sort
Developed by: sai vivek ragala
RegisterNumber: 23003676''' 
def max_marks(marks):
    marks.sort()
    max_mark = marks[-1]
    return max_mark
```
ii)	# To find the maximum marks using the list method max().
```Python
Developed by: sai vivek ragala
RegisterNumber: 23003676
'''
def max_marks(marks):
    large = max(marks)
    return large
```
iii) # To find the maximum marks without using builtin functions.
```Python
Developed by: sai vivek ragala
RegisterNumber: 23003676
'''
def max_marks(list1):
    max = list1[0]
    for i in list1:
        if i>max:
            max = i
    return max        
```
## Sample Input and Output
![Screenshot 2023-12-01 092020](https://github.com/RAGALASAIVIVEK/FindMaximum/assets/144979718/fd74e29c-4035-4f9b-8b7e-67e866fb8008)
![Screenshot 2023-12-01 092058](https://github.com/RAGALASAIVIVEK/FindMaximum/assets/144979718/8fd3e604-bd40-4f90-8173-c388a6c0cd42)
![Screenshot 2023-12-01 092136](https://github.com/RAGALASAIVIVEK/FindMaximum/assets/144979718/4a618bc2-95eb-4535-aa28-3207443b4460)


## Output:
![Screenshot 2023-12-01 092313](https://github.com/RAGALASAIVIVEK/FindMaximum/assets/144979718/d2091eb8-8386-43f4-bcb6-8bfb523eeb09)
![Screenshot 2023-12-01 092722](https://github.com/RAGALASAIVIVEK/FindMaximum/assets/144979718/1134e5bc-7ca3-4366-adb2-36fc23300616)
![Screenshot 2023-12-01 093046](https://github.com/RAGALASAIVIVEK/FindMaximum/assets/144979718/f3ffcf8a-6361-49b9-9bce-a890c151ea53)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
