<div align="center">
    <img align="center" src="https://github.com/tivereidoro/assets/assets/105525310/8d298662-9874-46b0-aabc-54f837bcc6a4" alt="alx_swe" width="60"  height="60"/>

---

### 0x05. N QUEENS
<img src="https://img.shields.io/badge/Algorithm-eed718"> &nbsp;<img src="https://img.shields.io/badge/Python-306998">

##
</div>

The `“0x05. N queens”` project is a classic problem in computer science and mathematics, known for its application of the backtracking algorithm to place N non-attacking queens on an N×N chessboard. To successfully complete this project, you will need to understand several key concepts and have access to resources that will help you grasp the necessary algorithms and techniques.

## Required Concepts:
1. **Backtracking Algorithms:**
    * Understanding how backtracking algorithms work to explore all potential solutions to a problem and backtrack when a solution cannot be completed.
    * [Backtracking Introduction](https://www.geeksforgeeks.org/introduction-to-backtracking-data-structure-and-algorithm-tutorials/)

2. **Recursion:**
    * Using recursive functions to implement backtracking algorithms.
    * [Recursion in Python](https://realpython.com/python-thinking-recursively/)

3. **List Manipulations in Python:**
    * Creating and manipulating lists, especially to store the positions of queens on the board.
    * [Python Lists](https://docs.python.org/3/tutorial/datastructures.html)

4. **Python Command Line Arguments:**
    * Handling command-line arguments with the `sys` module.
    * [Command Line Arguments in Python](https://docs.python.org/3.3/library/sys.html#sys.argv)

By studying these concepts and utilizing the resources provided, you will be equipped with the knowledge required to implement an efficient solution to the N queens problem using Python. This project not only tests programming and problem-solving skills but also offers an excellent opportunity to learn about algorithmic thinking and optimization techniques.

### Also see this : [Mock Technical Interview](https://www.youtube.com/watch?v=GneS80iYa7I)


## General Requirements
* Allowed editors: `vi`, `vim`, `emacs`
* All your files will be interpreted/compiled on Ubuntu 20.04 LTS using `python3` (version 3.4.3)
* All your files should end with a new line
* The first line of all your files should be exactly `#!/usr/bin/python3`
* A `README.md` file, at the root of the folder of the project, is mandatory
* Your code should use the `PEP 8` style (version 1.7.*)
* All your files must be executable

## Tasks 🎯
### 0. N queens: [0-nqueens.py](0-nqueens.py)

<div align="center">
<img alt=Judit-photo src='https://github.com/tivereidoro/alx-interview/assets/105525310/b4d9824e-934e-4f43-8c48-d6087ae47052'>
</div>

Chess grandmaster [Judit Polgár](https://en.wikipedia.org/wiki/Judit_Polg%C3%A1r), the strongest female chess player of all time


The N queens puzzle is the challenge of placing N non-attacking queens on an N×N chessboard. Write a program that solves the N queens problem.

* Usage: `nqueens N`
  * If the user called the program with the wrong number of arguments, print `Usage: nqueens N`, followed by a new line, and exit with the status `1`
* where N must be an integer greater or equal to `4`
  * If N is not an integer, print `N must be a number`, followed by a new line, and exit with the status `1`
  * If N is smaller than `4`, print `N must be at least 4`, followed by a new line, and exit with the status `1`
* The program should print every possible solution to the problem
  * One solution per line
  * Format: see example
  * You don’t have to print the solutions in a specific order
* You are only allowed to import the `sys` module

Read: [Queen](https://en.wikipedia.org/wiki/Queen_%28chess%29), [Backtracking](https://en.wikipedia.org/wiki/Backtracking)
```groovy
julien@ubuntu:~/0x08. N Queens$ ./0-nqueens.py 4
[[0, 1], [1, 3], [2, 0], [3, 2]]
[[0, 2], [1, 0], [2, 3], [3, 1]]
julien@ubuntu:~/0x08. N Queens$ ./0-nqueens.py 6
[[0, 1], [1, 3], [2, 5], [3, 0], [4, 2], [5, 4]]
[[0, 2], [1, 5], [2, 1], [3, 4], [4, 0], [5, 3]]
[[0, 3], [1, 0], [2, 4], [3, 1], [4, 5], [5, 2]]
[[0, 4], [1, 2], [2, 0], [3, 5], [4, 3], [5, 1]]
julien@ubuntu:~/0x08. N Queens$
```

---

#### Code Editor used: Mostly `VS-Code`; also  `Vim`
##
#### AUTHOR 👨🏽‍💻:
[_Tivere IDORO_](https://github.com/tivereidoro)

<hr>
