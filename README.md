# List Operations in Python

This Python script demonstrates how to create and manipulate a list using basic list operations such as `append`, `insert`, `extend`, `pop`, `sort`, and `index`.

## Steps Performed

1. **Create an empty list**
   ```python
   my_list = []
Initializes an empty list.

Append elements
Adds 10, 20, 30, and 40 to the list using append().

my_list.append(10)
my_list.append(20)
my_list.append(30)
my_list.append(40)
Insert a value
Inserts 15 at the second position (index 1) using insert().

my_list.insert(1, 15)
Extend the list
Adds multiple elements [50, 60, 70] to the end of the list using extend().

my_list.extend([50, 60, 70])
Remove the last element
Removes the last element using pop().

my_list.pop()
Sort the list
Sorts the list in ascending order using sort().

my_list.sort()
Find the index of a value
Finds the position of the value 30 using index() and prints it.

index_30 = my_list.index(30)
print("Index of 30:", index_30)
Print the final list
Prints the final sorted list.

Example Output
Step 1: []
Step 2: [10, 20, 30, 40]
Step 3: [10, 15, 20, 30, 40]
Step 4: [10, 15, 20, 30, 40, 50, 60, 70]
Step 5: [10, 15, 20, 30, 40, 50, 60]
Step 6: [10, 15, 20, 30, 40, 50, 60]
Step 7: Index of 30 = 3
Final list: [10, 15, 20, 30, 40, 50, 60]
