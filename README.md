# Selection sort and Insertion sort
## Aim:
To write a program to perform selection sort and insertion sort using python programming.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Selection Sort Algorithm:
1.	Set the first unsorted element as the minimum
2.	For each of the unsorted elements, check if the element < current minimum.
3.	If yes, set the element as the new minimum.
4.	Swap minimum with first unsorted position.
5.	Repeat the steps 2 and 3 for all the elements in the array.
## Insertion Sort Algorithm:
1.	Set the first element as sorted element j.
2.	For each unsorted element X, check if current sorted element j >X.
3.	If yes, move sorted element to the right by 1.
4.	Break the loop and insert X.
5.	Repeat the steps 2 to 4 for sorting all the elements in the array.
## Program:
i)	#Selection Sort
```
Program to sort the elements in the list using the Selection Sort algorithm.
Developed by:SRINIDHI SENTHIL
RegisterNumber: 22001408
'''
def selection_sort(nums):
# write your code here using selection sort
for i in range(len(nums)):
low_index=i
    for j in range(i+1,len(nums)):
        if nums[j]<nums[low_index]:
        low_index=j
    nums[i],nums[low_index]=nums[low_index],nums[i]
return nums  
  
```
ii)	#Insertion Sort
```
Program to sort the elements in the list using the Insertion Sort algorithm.
Developed by: K.SANTHANA LAKSHMI
RegisterNumber: 212222240091
'''
def insertion_sort(nums):
# Write your code here to sort the elements in the list using Insertion sort
algorithm
for i in range(1,len(nums)):
item=nums[i]
j=i-1
while j>=0 and nums[j]>item:
nums[j+1]=nums[j]
j-=1
nums[j+1]=item
return nums
list_of_nums = eval(input())
print(insertion_sort(list_of_nums))
# use the insertion sort function to get the sorted list
# print the sorted list

```

## Output:

i) #Selection Sort

![image](https://github.com/santhanalakshmi04/Sorting-Algorithm/assets/119475762/866c7b35-1f32-4a95-a214-7af902259693)

ii)#Insertion Sort

![image](https://github.com/santhanalakshmi04/Sorting-Algorithm/assets/119475762/cdfc141a-1482-4e17-b615-cd0b7254e5a2)

## Result:
Thus the program is written to perform selection sort and insertion sort using python programming.
