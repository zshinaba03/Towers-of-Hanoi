# Towers of Hanoi Solver
This project is an implementation of the classic Towers of Hanoi problem using stacks in Python. It was created for a data structures class to demonstrate the use of recursion and stacks to solve the problem efficiently.

## Project Description
The Towers of Hanoi is a mathematical puzzle where you have three rods and n disks of different sizes. The objective is to move all the disks from the source rod to the destination rod, following these rules:

1. Only one disk can be moved at a time.
2. A disk can only be placed on top of a larger disk or on an empty rod.
3. All disks start on the source rod, ordered by size with the largest at the bottom.

This project implements the recursive solution to the Towers of Hanoi problem using a custom Stack class to manage the disks on each rod. The solution includes:

* Recursive Function: A recursive function Hanoi_rec that solves the problem by dividing it into smaller subproblems.
* Stack Implementation: A stack-based approach to simulate the rods and manage the disk movements.
* Performance Measurement: The timeit library is used to measure the runtime of the solution.


## Code Structure 
* **Hanoi_rec(n, s, a, d)**: The recursive function that solves the Towers of Hanoi problem. It moves n disks from the source stack (s) to the destination stack (d) using an auxiliary stack (a).
* **Hanoi(n):** Initializes the stacks and calls the recursive function to solve the problem for n disks.
* **Stack:** A custom stack class (imported from Stack.py) used to represent each rod in the puzzle.

* # Example Output

* The output includes the steps taken to move the disks and the total time taken to compute the solution:

* 2 <Stack: [2, 1, 0]> <Stack: []> <Stack: []>
2 <Stack: []> <Stack: [2, 1]> <Stack: [0]>
...
computed Hanoi(3) in 0.00012 seconds.

# What I Learned

* Understood and applied recursion in problem solving
* Implemented and used the stack data structure in Python
* Measured and analyzed the performance of recursive algorithms

