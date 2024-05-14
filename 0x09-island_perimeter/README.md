<div align="center">
    <img align="center" src="https://github.com/tivereidoro/assets/assets/105525310/8d298662-9874-46b0-aabc-54f837bcc6a4" alt="alx_swe" width="60"  height="60"/>
    
---
### 0x09. ISLAND PERIMETER
<img src="https://img.shields.io/badge/Algorithm-eed718"> &nbsp;<img src="https://img.shields.io/badge/Python-306998">
</div>

The `“0. Island Perimeter”` project requires the knowledge of algorithms, data structures (specifically matrices or 2D lists), and iterative or conditional logic to solve a geometric problem within a grid context. The goal is to calculate the perimeter of a single island in a grid, where the grid is represented by a 2D array of integers. Understanding how to navigate and analyze 2D arrays and apply logical operations to determine the conditions for perimeter calculation is crucial for this task.

## Required Concepts:
1. **2D Arrays (Matrices):**

    * Accessing and iterating over elements in a 2D array.
    * Understanding how to navigate through adjacent cells (horizontally and vertically).

2. **Conditional Logic:**

    * Applying conditions to determine whether a cell contributes to the perimeter of the island.

3. **Counting Techniques:**

    * Developing a method to count the edges that contribute to the island’s perimeter.

4. **Problem-Solving Strategies:**

    * Breaking down the problem into smaller tasks, such as identifying land cells and calculating their contribution to the perimeter.

5. **Python Programming:**

    * Nested loops for iterating over grid cells.
    * Conditional statements to check the status of adjacent cells.

## Resources:
* **Python Official Documentation:**
    * [Nested Lists](https://docs.python.org/3/tutorial/datastructures.html#nested-list-comprehensions): Understand how lists work in Python.

* **GeeksforGeeks:**
    * [Python Multi-dimensional Arrays](https://www.geeksforgeeks.org/python-using-2d-arrays-lists-the-right-way/): Working with 2D arrays in Python.

* **TutorialsPoint:**
    * [Python Lists](https://www.tutorialspoint.com/python/python_lists.htm): How to create, access, and manipulate lists in Python.

* **YouTube Tutorials :** [Python 2D arrays and lists](https://www.youtube.com/watch?v=aNzepGawwCI)

### Also see this : [Mock Technical Interview](https://www.youtube.com/watch?v=fFgEM6CMQc4)

## General Requirements:

* Allowed editors: `vi`, `vim`, `emacs`
* All your files will be interpreted/compiled on Ubuntu 20.04 LTS using `python3` (version 3.4.3)
* All your files should end with a new line
* The first line of all your files should be exactly `#!/usr/bin/python3`
* A `README.md` file, at the root of the folder of the project, is mandatory
* Your code should use the `PEP 8` style (version 1.7)
* You are not allowed to import any module
* All modules and functions must be documented
* All your files must be executable

## Task 🎯
### 0. Island Perimeter: [0-island_perimeter.py](0-island_perimeter.py)
Create a function `def island_perimeter(grid):` that returns the perimeter of the island described in `grid`:

* `grid` is a list of list of integers:
   * 0 represents water
   * 1 represents land
   * Each cell is square, with a side length of 1
   * Cells are connected horizontally/vertically (not diagonally).
   * grid is rectangular, with its width and height not exceeding 100
* The `grid` is completely surrounded by water
* There is only one island (or nothing).
* The island doesn’t have “lakes” (water inside that isn’t connected to the water surrounding the island).

```groovy
guillaume@ubuntu:~/0x09$ cat 0-main.py
#!/usr/bin/python3
"""
0-main
"""
island_perimeter = __import__('0-island_perimeter').island_perimeter

if __name__ == "__main__":
    grid = [
        [0, 0, 0, 0, 0, 0],
        [0, 1, 0, 0, 0, 0],
        [0, 1, 0, 0, 0, 0],
        [0, 1, 1, 1, 0, 0],
        [0, 0, 0, 0, 0, 0]
    ]
    print(island_perimeter(grid))

guillaume@ubuntu:~/0x09$ 
guillaume@ubuntu:~/0x09$ ./0-main.py
12
guillaume@ubuntu:~/0x09$
```
---
#### Code Editor used: Mostly `VS-Code`; also  `Vim`
##
## AUTHOR 👨🏽‍💻:
[_Tivere IDORO_](https://github.com/tivereidoro)

<hr>
