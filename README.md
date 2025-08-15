# README

## Overview

This Python script demonstrates basic list operations step-by-step. It starts by creating an empty list, then performs various modifications such as appending elements, inserting an element at a specific position, extending the list with another list, removing an element, sorting the list, and finding the index of a specific value. Finally, it prints the index of the value `30` and the final state of the list.

***

## Steps Explained

1. **Create an empty list**
   ```python
   my_list = []
   ```
   Initializes an empty list called `my_list`.

2. **Append elements 10, 20, 30, 40**
   ```python
   my_list.append(10)
   my_list.append(20)
   my_list.append(30)
   my_list.append(40)
   ```
   Adds elements `10`, `20`, `30`, and `40` to the end of the list.

3. **Insert 15 at the second position (index 1)**
   ```python
   my_list.insert(1, 15)
   ```
   Inserts the value `15` at index `1`, shifting the existing elements to the right.

4. **Extend with another list [50, 60,`python
   my_list.extend([50, 60, 70])
   ```
   Adds the elements `50`, `60`, and `70` to the end of `my_list`.

5. **Remove the last element**
   ```python
   my_list.pop()
   ```
   Removes the last element (`70`) from the list.

6. **Sort the list in ascending order**
   ```python
   my_list.sort()
   ```
   Sorts the elements of the list in ascending order.

7. **Find and print the index of value 30**
   ```python
   index_of_30 = my_list.index(30)
   print("Index of 30:", index_of_30)
   ```
   Finds the position of the value `30` in the sorted list and prints it.

8. **Print the final list**
   ```python
   print("Final list:", my_list)
   ```
   Displays the final state of the list after all modifications.

***

## Expected Output

```
Index of 30: 4
Final list: [10, 15, 20, 30, 40, 50, 60]
```

***

## Usage

Run the script in any Python 3 environment. It requires no external libraries and purely demonstrates common list operations. This example is suitable for beginners learning list manipulation in Python.
