# Experiment–3  
## Lists in Python: Indexing, Slicing, and List Methods

### Aim
To study Python lists and perform operations such as indexing, slicing, traversal, and manipulation using built-in list methods.

### Objectives
- Create and access lists in Python  
- Perform indexing and slicing operations  
- Understand list mutability  
- Apply commonly used list methods  
- Traverse and modify list elements  

### Theory

#### 1. Introduction to Lists
A **list** is a built-in data structure in Python used to store multiple values in a single variable. Lists are written using square brackets `[]`, with elements separated by commas. Lists are dynamic, meaning their size can change during program execution.

#### 2. Characteristics of Python Lists
Python lists have the following important properties:
- **Ordered:** Elements are stored in the order of insertion  
- **Indexed:** Each element is associated with an index starting from 0  
- **Mutable:** Elements can be changed, added, or removed  
- **Heterogeneous:** Can store elements of different data types  
- **Allows Duplicates:** Duplicate values are permitted  

#### 3. List Creation
Lists can be created using:
- Square brackets: `list = [1, 2, 3]`  
- `list()` constructor  
Lists can also be **nested**, allowing lists inside other lists.

#### 4. Indexing in Lists
Indexing allows access to individual elements of a list.
- **Positive indexing:** Starts from 0 (left to right)  
- **Negative indexing:** Starts from -1 (right to left)  

Indexing helps retrieve or update specific elements efficiently.

#### 5. Slicing in Lists
Slicing is used to extract a portion (sublist) from a list.

**Syntax:**  
`list_name[start : end : step]`

- `start` – starting index (included)  
- `end` – ending index (excluded)  
- `step` – interval between elements  

Slicing does not alter the original list.

#### 6. Mutability of Lists
Lists are mutable, meaning their contents can be modified after creation. This allows:
- Updating existing elements  
- Adding new elements  
- Removing unwanted elements  

This property makes lists suitable for dynamic data storage.

#### 7. List Traversal
List traversal refers to accessing each element of the list sequentially. It is commonly done using:
- `for` loop  
- `while` loop  

Traversal is useful for searching, updating, and processing list elements.

#### 8. List Methods
Python provides built-in methods to manipulate lists, such as:
- `append()` – Adds element at the end  
- `insert()` – Inserts element at a specific index  
- `remove()` – Removes specified element  
- `pop()` – Removes element by index  
- `sort()` – Sorts elements  
- `reverse()` – Reverses list order  
- `count()` – Counts occurrences of an element  
- `index()` – Returns index of an element  

#### 9. Built-in Functions for Lists
Common functions used with lists include:
- `len()` – Returns number of elements  
- `max()` – Returns maximum value  
- `min()` – Returns minimum value  
- `sum()` – Returns sum of numeric elements  

### Applications / Programs Included
- Student marks management system  
- Grocery shopping list  
- Attendance register  
- Mobile contact list  
- Temperature analysis using slicing  

### Conclusion
Python lists are versatile data structures that support efficient storage and manipulation of data. Features like indexing, slicing, mutability, and built-in methods make lists essential for solving real-world programming problems.
