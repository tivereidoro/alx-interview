<p align="center">
    <img align="center" src="https://github.com/tivereidoro/assets/assets/105525310/8d298662-9874-46b0-aabc-54f837bcc6a4" alt="alx_swe" width="60"  height="60"/>
</p>

---

<div align="center">

## 0x02. MINIMUN OPERATIONS
<img src="https://img.shields.io/badge/Algorithm-eed718"> &nbsp;<img src="https://img.shields.io/badge/Python-306998">
</div>

<p align="justify">For this project, you will need to understand several key algorithmic and mathematical concepts to devise a solution that efficiently calculates the minimum number of operations to achieve a given number of characters using only “Copy All” and “Paste” operations. Here is a list of concepts and resources that will be helpful: </p>

### Concepts Needed:
1. [**Dynamic Programming** (GeeksforGeeks)](https://www.geeksforgeeks.org/dynamic-programming/)

2. [**Prime Factorization** (Khan Academy)](https://www.khanacademy.org/math/pre-algebra/pre-algebra-factors-multiples/pre-algebra-prime-factorization-prealg/v/prime-factorization)

3. [**How to optimize Python code**](https://stackify.com/how-to-optimize-python-code/)

4. [**Greedy Algorithms** (GeeksforGeeks)](https://www.geeksforgeeks.org/greedy-algorithms/)

5. [**Python Functions** (Python Official Documentation)](https://docs.python.org/3/tutorial/controlflow.html#defining-functions)

<p align="justify">By studying these concepts and utilizing the resources provided, you will be equipped to tackle the “Minimum Operations” problem effectively, applying both mathematical reasoning and programming skills to find the most efficient solution.

### Also see this: [Mock Technical Interview](https://www.youtube.com/watch?v=h4i4kjwncoU) 🧰 


### Task 0. Minimum Operations: [0-minoperations.py](0-minoperations.py)
In a text file, there is a single character `H`. Your text editor can execute only two operations in this file: `Copy All` and `Paste`. Given a number `n`, write a method that calculates the fewest number of operations needed to result in exactly `n` `H` characters in the file.

* Prototype: `def minOperations(n)`
* Returns an integer
* If `n` is impossible to achieve, return `0`

**Example:**

`n = 9`

`H` => `Copy All` => `Paste` => `HH` => `Paste` =>`HHH` => `Copy All` => `Paste` => `HHHHHH` => `Paste` => `HHHHHHHHH`

Number of operations: `6`
```groovy
carrie@ubuntu:~/0x02-minoperations$ cat 0-main.py
#!/usr/bin/python3
"""
Main file for testing
"""

minOperations = __import__('0-minoperations').minOperations

n = 4
print("Min # of operations to reach {} char: {}".format(n, minOperations(n)))

n = 12
print("Min # of operations to reach {} char: {}".format(n, minOperations(n)))

carrie@ubuntu:~/0x02-minoperations$
carrie@ubuntu:~/0x02-minoperations$ ./0-main.py
Min number of operations to reach 4 characters: 4
Min number of operations to reach 12 characters: 7
carrie@ubuntu:~/0x02-minoperations$
```
<!--
# Reference 📚
For those who have been challenged by the task minimum operations.

Let's say you are given n = 100, so the minimum operations need to copy and paste H can be calculated as:

1) You don't have to copy and paste 100 times. So what you can do is, finding the half.  If you have the first 50 'H's is your text file, then you can copy all and paste it.

Example:
```groovy
n = 100
100/2 = 50. 
Number of operation one= 2
n is now: 50
````

2) Repeat the process until n becomes 1.
```groovy
n = 50
50/2= 25
Number of operation two =  2

n = 25
25/2 ❌
25/3 ❌
25/4 ❌
25/5 ✅

25/5=5
Number of operation three = 5

n = 5
5/5= 1
Number of operation four = 5
```

At last n becomes: `1`, add up all the above operations.

Finally the number of operations: `2+2+5+5=14`

So the minimum operations to copy and paste 'H' 100 times is `14`.

## FeedBack from Peers:
1. If you really think about it, it's the sum of prime factors, the math is mathing....😆
-->
---

#### Code Editor used: Mostly `VS-Code`; also  `Vim`
##
#### AUTHOR 👨🏽‍💻:
[_Tivere IDORO_](https://github.com/tivereidoro)

<hr>
