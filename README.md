# EX:7 SORTING
# DATE:27/9/24
# REGISTER NUMBER:212222040046
# Aim:
Write a python program for sorting and inspect for failures.
# Algorithm:
1. Start the program.
2. Get the number of elements from user
3. Get the elements to be sorted
4. Traverse the array and sort the elements one by one
5. Print the sorted array
6. Stop the program.
# Program:
```
n=int(input("Enter the number of elements:"))
arr=[]
try:
for i in range(n):
a=float(input("Enter the element:"))
arr.append(a)
for i in range(n):
for j in range(n):
if(arr[i]<arr[j):
temp = arr[i]
arr[i] = arr[j]
arr[j] = temp
print(“The array after sorting: ”)
for i in range(n):
print(arr[i],end=’ ’)
except ValueError:
print(“Enter a valid number”)
```
# Output:
![Screenshot 2024-11-14 194911](https://github.com/user-attachments/assets/c3f0da98-e653-4e01-a92e-5eb3a78243f4)
# Result:
Thus, a program to check sorting has been written and test cases have been written and verified
successfully.


