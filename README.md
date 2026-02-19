# Study-of-Tuples-In-Python
 Experiment 4
Name:Aarya Yugansh Nirwan

PRN: 25070123004

Batch: ENTC A1

Title

Tuples in Python: Creation, Access, and Operations 

Aim
To understand Python tuples and perform operations such as creation, indexing, slicing, and the use of built-in functions.

Objectives
To understand the fundamental concept of tuples in Python.

To study the characteristics and specific advantages of using tuples.

To perform indexing and slicing operations on tuple data.

To apply various built-in tuple functions.

To understand the concept of immutability regarding tuples.

Theory on Tuples
A tuple is an ordered collection of elements in Python. While it is similar to a list, its primary distinction is being immutable in nature. Tuples are defined using parentheses ( ), with elements separated by commas.
+1


Example: (10, 20, 30) 

Characteristics of Tuples

Ordered: Elements maintain a specific sequence.


Indexed: Elements can be accessed via their position.


Immutable: Once created, a tuple cannot be changed.


Duplicates: Allows for the storage of duplicate values.


Heterogeneous: Can store various data types simultaneously.

Advantages of Tuples
They execute faster than lists.

They ensure data integrity because values cannot be modified.

They are ideal for storing fixed data such as coordinates, days of the week, or database records.

Tuple Operations
1. Creation
Tuples can be initialized using parentheses, through tuple packing (no parentheses), or by using the tuple() constructor. For a single-element tuple, a trailing comma is required, such as (10,).
+1

2. Indexing
Elements are accessed using index numbers starting from 0. Python supports both positive indexing and negative indexing for tuples.
+1

3. Slicing
Slicing extracts a specific portion of a tuple using the syntax: tuple_name[start : end : step].


Start: The index where slicing begins (included).


End: The index where slicing stops (excluded).


Step: The optional gap between elements.

4. Immutability
After a tuple is created, elements cannot be added, removed, or updated. Any attempt to modify the tuple will result in an error.
+1

Built-in Functions and Comparisons
Function	Description
len()	
Returns the total number of elements.

max() / min()	
Finds the maximum or minimum value in the tuple.

sum()	
Calculates the sum of all elements.

count()	
Counts the occurrences of a specific element.

index()	
Finds the index of a specific element.


Difference Between List and Tuple 

List	Tuple
Mutable 

Immutable 

Uses square brackets [ ] 

Uses parentheses ( ) 

Slower performance 

Faster performance 

Dynamic size 

Fixed size 

Problem Statements

Student Results: Store an exam result (Subject, Marks, Grade) in a tuple, unpack the values into variables, and check if the marks are 75 or higher to print "Distinction".
+1


Attendance Record: Store weekly attendance ("P" for Present, "A" for Absent) in a tuple, count the total present and absent days, and notify if the employee was absent at least once.
+1

Conclusion
Python tuples were studied, and various operations including creation, indexing, slicing, packing, unpacking, and built-in functions were successfully implemented.
