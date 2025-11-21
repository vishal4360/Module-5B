# NumPy Program: Column-wise Sorting of a 2D Array

## 🎯 Aim
To write a *NumPy* program that sorts the elements in each column of a given 2D array in ascending order.

## 🧠 Algorithm

1. *Import NumPy*: Start by importing the NumPy library.
2. *Get Input*: Accept a 2D NumPy array from the user.
3. *Sort Column-wise*: Use the np.sort() function with axis=0 to sort each column in ascending order.
4. *Store Result*: Store the sorted result in a new array.
5. *Display Output*: Print the original array and the column-wise sorted array.

## 🧾 Program
```
import numpy as np 
a=np.array(eval(input())) 
print("Given array") 
print(end=" ") 
print(a) 
print() 
print(np.sort(a,axis=0))
```
## Output:
![WhatsApp Image 2025-10-19 at 20 02 57_d0e3624a](https://github.com/user-attachments/assets/0e66977c-c84e-40ac-a278-7e829ad11033)


## Result:
The program has been executed successfully.
