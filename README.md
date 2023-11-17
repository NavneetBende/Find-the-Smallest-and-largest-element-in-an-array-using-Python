# Find-the-Smallest-and-largest-element-in-an-array-using-Python

Method Discussed are given below :
Method 1 : Using Iteration.
Method 2 : Using Sort() function.
Method 3 : Using max() and min() function
Method 1 :
Take a variable say mini to store the minimum element of the array and maxi to store the maximum element.
Set mini = arr[0] and maxi = arr[0]
Run a loop over the array
Check if(arr[i]<mini) then set mini = arr[i]
Also check if(arr[i]>maxi) then set maxi = arr[i]
After complete iteration print mini and maxi.
 
Method 1 : Code in Python
Run
arr = [10, 89, 9, 56, 4, 80, 8]
mini = arr[0]
maxi = arr[0]

for i in range(len(arr)):
  if arr[i] < mini: mini = arr[i] 
  
if arr[i] > maxi: maxi = arr[i]

print (mini)
print (maxi)
Output :
4

89
Method 2 :
Sort the array using inbuilt sort()function
Minimum element is at index 0 and maximum is at index -1
So, print(arr[0])
And, print(arr[-1])
smallest and largest element in an array using python
Related Pages
Find Largest element in an array
 
Find Smallest Element in an Array
 
Find Second Smallest Element in an Array

Calculate the sum of elements in an array 

Reverse an Array

Method 2 : Code in Python
Run
arr = [10, 89, 9, 56, 4, 80, 8]
arr.sort()

print (arr[0])
print (arr[-1])
Output :
4

89
Method 3 :
Using inbuilt function min(arr) , it return minimum element of the array.
Similarly max(arr) return the maximum element of the array.
Method 3 : Code in Python
Run
arr = [10, 89, 9, 56, 4, 80, 8]

print (min(arr))
print (max(arr))
Output :
4

89
