# Recursive Algorithms

Recursive algorithms are a fundamental concept in computer science and can be applied to a wide range of problems. Here are several practical examples of recursive algorithms that high school students can relate to and utilize, often making complex problems more manageable:

1. **[Factorial Calculation](https://github.com/Pete-ComSci/recursive_algorithms/tree/8f84b94a93be0eb1b04e10ff6c0bdc7a387045e0/factorial_calculation)**:
   - **Problem**: Calculate the factorial of a number (n!), which is the product of all positive integers up to that number.
   - **Practical Use**: Factorial calculations are used in permutations and combinations, probability problems, and in various mathematical formulations.

2. **[Fibonacci Sequence](https://github.com/Pete-ComSci/recursive_algorithms/tree/b929aa2fadcf036ff4dc75cdcfd086fe14f9f30d/fibonacci_sequence)**:
   - **Problem**: Generate the Fibonacci sequence, where each number is the sum of the two preceding ones, starting from 0 and 1.
   - **Practical Use**: The Fibonacci sequence is applicable in teaching concepts of recursion, in mathematical computations, and even in understanding nature's patterns like the branching of trees, the arrangement of leaves on a stem, or the fruitlets of a pineapple.

3. **[Tower of Hanoi](https://github.com/Pete-ComSci/recursive_algorithms/tree/179717b833c897d9ba229a0b680e8c370bfd0341/tower_of_hanoi)**:
   - **Problem**: Solve the Tower of Hanoi puzzle where you move a stack of disks from one rod to another, following specific rules.
   - **Practical Use**: Apart from being a popular puzzle, the Tower of Hanoi problem teaches the concept of recursion and problem-solving strategies. It's also used in understanding recursive data structures and algorithms.

4. **[Directory Traversal](https://github.com/Pete-ComSci/recursive_algorithms/tree/7fbc9b87d2adb1b0b7e037cfaf74c6ed86f57cb1/directory_traversal)**:
   - **Problem**: Traverse and list all files in a directory, including subdirectories and their files.
   - **Practical Use**: This is practical in file management systems where you need to navigate through directories and their subdirectories, displaying contents or organizing files.

5. **[Binary Search](https://github.com/Pete-ComSci/recursive_algorithms/tree/97597de4b098f0741794d9f0a334c278bd75df5c/binary_search)**:
   - **Problem**: Find the position of an element in a sorted array by repeatedly dividing the search interval in half.
   - **Practical Use**: Binary search is used in searching applications where the data is sorted. It’s a fundamental algorithm in computer science and is used in optimizing search problems.

6. **Graph Traversals (DFS/BFS)**:
   - **[Depth-First Search (DFS)](https://github.com/Pete-ComSci/recursive_algorithms/tree/dcdb0a05ed10cde4f8600408967f15fd847d4048/depth_first_search)** and **[Breadth-First Search (BFS)](https://github.com/Pete-ComSci/recursive_algorithms/tree/dcdb0a05ed10cde4f8600408967f15fd847d4048/breadth_first_search)** are used to traverse or search tree or graph data structures.
   - **Practical Use**: These algorithms are used in pathfinding and graph analysis, finding connected components in a network, solving puzzles with only one solution, such as mazes.

7. **Merge Sort Algorithm** (as discussed):
   - **Problem**: Sort a list of elements.
   - **Practical Use**: Merge Sort is used in sorting applications where stability (preserving the input order of equal elements) is important. It’s particularly useful in sorting linked lists.

8. **[Backtracking Algorithms](https://github.com/Pete-ComSci/recursive_algorithms/tree/dcdb0a05ed10cde4f8600408967f15fd847d4048/backtracking_n_queens_problem)**:
   - **Problem**: Solve problems by trying to build a solution incrementally and removing solutions that fail to satisfy the constraints of the problem (like solving a maze, finding the arrangement of queens on a chessboard - N-Queens problem, etc.).
   - **Practical Use**: Backtracking is used in constraint satisfaction problems like crosswords, verbal arithmetic, Sudoku, and many other puzzle games.

These examples not only demonstrate the power of recursion in simplifying complex problems but also have practical applications that students can relate to, making them excellent teaching tools for understanding and applying recursion.

A comparison table for the practical recursive algorithms mentioned, detailing their explanations, examples, and complexities:

| Algorithm          | Explanation                                                                                                                                              | Example Before                           | Example After                            | Best Case      | Average Case   | Worst Case     | Best Usage Scenario                                                                                     |
|--------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------|------------------------------------------|----------------|----------------|----------------|---------------------------------------------------------------------------------------------------------|
| [Factorial Calculation](https://github.com/Pete-ComSci/recursive_algorithms/tree/8f84b94a93be0eb1b04e10ff6c0bdc7a387045e0/factorial_calculation)          | Calculates the product of all positive integers up to a given number (n!).                                                                                | n = 5                                    | 5! = 120                                 | O(n)           | O(n)           | O(n)           | Used in permutations, combinations, and various mathematical calculations.                             |
| [Fibonacci Sequence](https://github.com/Pete-ComSci/recursive_algorithms/tree/b929aa2fadcf036ff4dc75cdcfd086fe14f9f30d/fibonacci_sequence) | Generates a sequence where each number is the sum of the two preceding ones.                                                                               | n = 5 (0, 1, 1, 2, 3)                    | 5th Fibonacci number = 5                  | O(2^n) (naive) | O(n) (optimized with memoization) | O(2^n) (naive) | Teaching recursion, understanding nature's patterns, and in mathematical computations.                |
| [Tower of Hanoi](https://github.com/Pete-ComSci/recursive_algorithms/tree/179717b833c897d9ba229a0b680e8c370bfd0341/tower_of_hanoi)     | Solve the puzzle by moving disks from one rod to another, following certain rules.                                                                        | 3 disks on rod A                         | 3 disks on rod C                         | O(2^n)         | O(2^n)         | O(2^n)         | Teaching problem-solving strategies, understanding recursive algorithms, and puzzle games.             |
| [Directory Traversal](https://github.com/Pete-ComSci/recursive_algorithms/tree/7fbc9b87d2adb1b0b7e037cfaf74c6ed86f57cb1/directory_traversal)| Traverses and lists all files in a directory and its subdirectories.                                                                                      | Folder with nested subfolders and files  | List of all files and subfolders         | O(n)           | O(n)           | O(n)           | File management systems, organizing files, and navigating through directories.                        |
| [Binary Search](https://github.com/Pete-ComSci/recursive_algorithms/tree/97597de4b098f0741794d9f0a334c278bd75df5c/binary_search)      | Finds the position of an element in a sorted array by repeatedly dividing the search interval in half.                                                    | [1, 3, 5, 7, 9], Target = 7              | Index = 3                                | O(1)           | O(log n)       | O(log n)       | Searching applications where data is sorted, optimizing search problems.                              |
| [DFS](https://github.com/Pete-ComSci/recursive_algorithms/tree/dcdb0a05ed10cde4f8600408967f15fd847d4048/depth_first_search)/[BFS](https://github.com/Pete-ComSci/recursive_algorithms/tree/dcdb0a05ed10cde4f8600408967f15fd847d4048/breadth_first_search)            | Traverse or search tree or graph data structures. DFS uses a stack, while BFS uses a queue.                                                               | Graph or tree                            | Nodes visited in DFS/BFS order           | O(V+E)         | O(V+E)         | O(V+E)         | Pathfinding, graph analysis, finding connected components, and puzzle solutions.                     |
| Merge Sort         | Divides the array into halves, sorts them, and merges them.                                                                                                | [38, 27, 43, 3, 9]                       | [3, 9, 27, 38, 43]                       | O(n log n)     | O(n log n)     | O(n log n)     | Large datasets where a stable sort and consistent performance are required.                           |
| [Backtracking Algorithms](https://github.com/Pete-ComSci/recursive_algorithms/tree/dcdb0a05ed10cde4f8600408967f15fd847d4048/backtracking_n_queens_problem)       | Solves problems incrementally, removing solutions that fail to satisfy the constraints of the problem.                                                     | Puzzle board (Sudoku, N-Queens)           | Solution to the puzzle                   | O(m^n) (depends on problem specifics) | Depends on problem and pruning efficiency | O(m^n) (depends on problem specifics) | Constraint satisfaction problems, puzzles, and in situations where exhaustive search is necessary. |

In the table, V represents the number of vertices and E represents the number of edges in the graph for graph-based algorithms (DFS/BFS). The complexities for backtracking algorithms can vary significantly based on the problem specifics and how efficiently the search space can be pruned. The best-case scenario for binary search assumes the target value is at the middle of the array, hence O(1). The usage scenarios provide a general idea of where these algorithms can be applied effectively.
