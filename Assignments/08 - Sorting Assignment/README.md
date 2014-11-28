Task(s)
-------
You **may** work in pairs for this assignment.

1. Create an array (or ArrayList) of objects that you used from the Objects assignment.  Each object in the array should have a random numerical value within the object that you can use for sorting (a PVector, a diameter, etc.).
2. Create a selectionSort() function which uses the selection sort algorithm (create this yourself, do not use built-in functions to do all the heavy lifting).
3. On keyPressed, use your selectionSort() function to sort your objects in ascending order, and display them accordingly.
4. On mousePressed, create a new randomly generated array of objects.
5. In a block comment in your main file, compare the run time and worst-case computational complexity of the selectionSort() algorithm vs a merge sort algorithm.  See Notes section below for more info

Submission Item(s)
------------------
Hand in the work to the IN folder

Due Date(s)
-----------
This assignment is due by December 8th, 2014 - **no exceptions**
(Note: multiple assignments are due on this day)

Rubric(s)
---------
This rubric is out of a total of 12

| | 0 | 1 | 2 | 3 | 4 |
|---| --- | --- | --- | --- | --- |
|C2.3: Compare the efficiency of sorting algorithms using run times and computational complexity analysis  | | | | | |
|A4.1: Work independently, using support documentation to resolve syntax issues during software development  | | | | | |
|A4.3: Create fully documented program code according to industry standards (**no javadocs req**, block comments, line comments, etc.)  | | | | | |

Notes:
------
To roughly calculate the computational complexity of a sorting algorithm (also known as "Big-Oh" notation), you count the number of statements executed, the number of iterations of a loop, and/or the number of comparisons performed.

For example, the [Bubble Sort] (http://mathbits.com/MathBits/Java/arrays/Bubble.htm) algorithm runs in O(n^2) time on average, and as a worst-case (read as "Oh n squared"), because of the two nested _for_ loops, which runs through and compares every single item with all items previous to it.