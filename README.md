# Data Structures - Lists, Dictionaries, Sets and Conditional Statements

This Jupyter notebook contains hands-on Python exercises with lists, dictionaries and sets, along with decision-making using conditional statements. It demonstrates how to create, modify and access these collections, perform set operations, and categorize user input using if-elif-else logic.

## Concepts Used

### Lists
Ordered, mutable collections created with `[]`. They can hold duplicate values and elements can be changed after creation.

### append() Method
Adds a single element to the end of a list.

### insert() Method
Adds an element at a specific index, shifting the existing elements to the right.

### remove() Method
Deletes the first occurrence of a given value from a list.

### pop() Method
Removes and returns an element from a list. By default it removes the last element.

### extend() Method
Adds all elements of another list to the end of the existing list, instead of adding the list as a single item.

### sort() Method
Arranges list elements in order. Using `reverse=True` sorts in descending order. It modifies the list in place.

### max(), min() and sum()
Built-in functions that return the largest value, the smallest value and the total of a numeric list.

### List Indexing and Slicing
Positive indexes start at `0` and negative indexes start at `-1` from the end. Slicing with `[start:stop]` excludes the stop index, and `[::-1]` reverses the list.

### Dictionaries
Collections of key-value pairs created with `{}`. Keys must be unique and are used to access values.

### Accessing Dictionary Values
A value is retrieved by using its key, e.g. `student_marks["Anu"]`.

### Adding and Updating Dictionary Entries
Assigning a value to a new key adds a new entry, while assigning to an existing key updates its value.

### keys(), values() and items()
Return all keys, all values and all key-value pairs of a dictionary respectively.

### Sets
Unordered collections of unique elements created with `{}` or `set()`. Duplicate values are automatically removed.

### Set Immutability of Position
Sets are unordered, so they do not support indexing. Trying `my_set[4] = 's'` raises a `TypeError` because elements have no fixed position.

### Union and Intersection
`union()` (or `|`) combines all unique elements from both sets, while `intersection()` (or `&`) returns only the elements common to both.

### User Input and Type Conversion
`input()` reads text from the user, and `int()` or `float()` converts it to a number so it can be compared.

### Comparison and Logical Operators
Operators such as `>`, `<`, `>=`, `<=` and `and` are used to build conditions, e.g. `4 <= score <= 7`.

### if-elif-else Statements
Execute different blocks of code depending on which condition is true. Conditions are checked from top to bottom and only the first matching block runs.

### Input Validation
Checks that the score lies between 0 and 10 (inclusive) before categorizing it.

### print() Function
Displays labelled output for readability.

## Running the Code

Open the notebook in Jupyter Notebook or JupyterLab and run the cells in order.

To run it from a terminal instead, execute the notebook with:

```bash
jupyter nbconvert --to notebook --execute "Python2.Data_Structures-List,Dictionary,Set&Conditional_Statements.ipynb"
```
