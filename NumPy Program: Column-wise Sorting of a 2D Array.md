# NumPy Program: Column-wise Sorting of a 2D Array
## Name: GEETHU R
## Register No.: 212224040089
## 🎯 Aim
To write a **NumPy** program that sorts the elements in each column of a given 2D array in ascending order.

## 🧠 Algorithm

1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Accept a 2D NumPy array from the user.
3. **Sort Column-wise**: Use the `np.sort()` function with `axis=0` to sort each column in ascending order.
4. **Store Result**: Store the sorted result in a new array.
5. **Display Output**: Print the original array and the column-wise sorted array.

## 🧾 Program
~~~
import numpy as np
arr=np.array(eval(input()))
print("Given array")
print(arr)
print()
print(np.sort(arr,axis=0))
~~~

## Output
![numpy coloumn](https://github.com/user-attachments/assets/a416d529-78b4-4251-a636-cc67e0dc5ab0)

## Result
The program has been executed successfully.
