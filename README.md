### JAVASCRIPT DATA STRUCTURE AND ALGORITHMS

-> A data structure is a way of organizing data in a computer system. It defines how data is stored, processed, and accessed. Data structures are a fundamental part of coding and software development. 

-> Data structures are essential for two main reasons: they make the code more efficient, and they make the code easier to understand. When it comes to efficiency, data structures help the computer to run the code faster by organizing the data in a way that is easy for the computer to process.


# Why are data structures important?
* Efficient storage and retrieval: Data structures make it easier to store and retrieve data, especially large amounts of data. 

* Improved code quality: Data structures make code easier to understand and more efficient. 
Better problem solving: Data structures provide algorithms that help solve complex problems. 

* Faster program performance: Choosing the right data structure for a task can optimize the performance of a program. 

* Better decision making: Data structures can help improve decision-making skills.  

# How do data structures work? 
* Data structures are specialized formats for organizing data.
* Each data structure contains information about the data values, relationships between the data, and functions that can be applied to the data.
* There are many different types of data structures, each designed for a specific purpose.

## Big-O Notation (O-notation)
-> Big-O notation represents the upper bound of the running time of an algorithm. Therefore, it gives the worst-case complexity of an algorithm.
-> It is the most widely used notation for Asymptotic analysis.
-> It specifies the upper bound of a function.
-> The maximum time required by an algorithm or the worst-case time complexity.
-> It returns the highest possible output value(big-O) for a given input.
-> Big-O(Worst Case) It is defined as the condition that allows an algorithm to complete statement execution in the longest amount of time possible.

## Omega Notation (Ω-notation)
-> Omega notation represents the lower bound of the running time of an algorithm. Thus, it provides the best case complexity of an algorithm.

## Theta Notation (Θ-notation)
-> Theta notation encloses the function from above and below. Since it represents the upper and the lower bound of the running time of an algorithm, it is used for analyzing the average-case complexity of an algorithm.

## Problem Solving Approach
# Introduction to Problem solving
# Concrete example
# Break it down
# solve or simplify
# Look Back and refactor

## Problem solving patterns

# Frequency Counter pattern
* A "frequency counter pattern" is a programming technique that utilizes a data structure like an object or set to store the frequency (count) of each unique element within a collection (like an array or string), allowing for efficient comparison between different data sets by avoiding nested loops and improving time complexity, especially when dealing with problems requiring element frequency analysis. 

-> Key points about the frequency counter pattern:
* Purpose: To count how many times each element appears in a collection. 
* Data structure used: Typically, a JavaScript object where the element acts as the key and its count as the value. 
* Benefits:
    - Avoids nested loops, which often lead to quadratic time complexity. 
    - Enables efficient comparison between two collections based on element frequencies. 


-> exercise 
- anagram 
- Sorting Elements of an Array by Frequency
- Single Number


# Multiple Pointer pattern
* The multiple pointer pattern is a problem-solving technique that uses two or more pointers to traverse a data structure. The pointers move in different directions based on certain conditions. This technique is often used to solve problems involving searching, sorting, or finding patterns. 

-> How it works 
    - Create pointers that correspond to an index or position in a data structure
    - Move the pointers towards each other or in different directions based on conditions
    - Ensure that the pointers don't overlap

-> When to use it
    - When searching for a pair of values in a linear structure like an array, string, or linked list 
    - When searching for something that meets a condition 
    - When comparing two strings, such as to check for anagrams 

-> Benefits 
    - Efficient for solving problems with minimal space complexity
    - Can reduce time complexity by avoiding nested loops or unnecessary iterations

-> exercise :- 
    - count unique values challenge
    - Find the closest pair from two sorted arrays
    - Find the pair in array whose sum is closest to x
    - Find all triplets with zero sum
    - Find a triplet that sum to a given value
    - Find a triplet such that sum of two equals to third element
    - Find four elements that sum to a given value
    - Trapping Rain Water

# Sliding Window pattern
-> Sliding Window Technique is a method used to efficiently solve problems that involve defining a window or range in the input data (arrays or strings) and then moving that window across the data to perform some operation within the window. This technique is commonly used in algorithms like finding subarrays with a specific sum, finding the longest substring with unique characters, or solving problems that require a fixed-size window to process elements efficiently.

-> How to use Sliding Window Technique?
* 1. Fixed Size Sliding Window:
    - The general steps to solve these questions by following below steps:
    - Find the size of the window required, say K.
    - Compute the result for 1st window, i.e. include the first K elements of the data structure.
    - Then use a loop to slide the window by 1 and keep computing the result window by window.

* 2. Variable Size Sliding Window:
    - The general steps to solve these questions by following below steps:
    - In this type of sliding window problem, we increase our right pointer one by one till our condition is true.
    - At any step if our condition does not match, we shrink the size of our window by increasing left pointer.
    - Again, when our condition satisfies, we start increasing the right pointer and follow step 1.
    - We follow these steps until we reach to the end of the array.

* exercise
- To find the maximum sum of all subarrays of size K
- Smallest subarray with sum greater than a given value
- Find subarray with given sum in an array of non-negative integers
- Smallest window that contains all characters of string itself
- Find Subarray with given sum
- Sliding Window Maximum (Maximum of all subarrays of size K)
- Longest Sub-Array with Sum K
- Find maximum (or minimum) sum of a subarray of size k
- Smallest window in a String containing all characters of other String
- Length of the longest substring without repeating characters
- First negative integer in every window of size k
- Count distinct elements in every window of size k
- Smallest window that contains all characters of string itself
- Largest sum subarray with at-least k numbers
- Check if Permutation of Pattern is Substring

# Divide and Conquer Pattern 
* The divide and conquer design pattern is a computer science algorithm design pattern that breaks down a complex task into smaller sub-tasks. The goal is to solve the sub-tasks individually and then combine the solutions to solve the original problem.

-> How it works 
    - Divide: Break the problem into smaller sub-problems
    - Conquer: Solve the sub-problems individually
    - Combine: Combine the solutions to the sub-problems to solve the original problem

-> Benefits
    - Reduces time: The divide and conquer approach can be used to write fast algorithms. 
    - Reduces complexity: The divide and conquer approach can be used to reduce the complexity of non-trivial tasks. 
    - Parallel processing: The divide and conquer approach can be used to solve sibling units of work in parallel. 
    - Reuse: The divide and conquer approach can provide more opportunities for reuse. 

-> exercise
    - Square root of an integer
    - Maximum and minimum of an array using minimum number of comparisons
    - Find frequency of each element in a limited range array in less than O(n) time
    - Tiling Problem
    - Count Inversions
    - The Skyline Problem
    - Search in a Row-wise and Column-wise Sorted 2D Array
    - Allocate minimum number of pages
    - Modular Exponentiation (Power in Modular Arithmetic)

## Recursion
* The process in which a function calls itself directly or indirectly is called recursion and the corresponding function is called a recursive function.

* A recursive algorithm takes one step toward solution and then recursively call itself to further move. The algorithm stops once we reach the solution.

* Since called function may further call itself, this process might continue forever. So it is essential to provide a base case to 
terminate this recursion process.

-> Need of Recursion
    - Recursion helps in logic building. Recursive thinking helps in solving complex problems by breaking them into smaller subproblems.
    - Recursive solutions work as a a basis for Dynamic Programming and Divide and Conquer algorithms.
    - Certain problems can be solved quite easily using recursion like Towers of Hanoi (TOH), Inorder/Preorder/Postorder Tree Traversals, DFS of Graph, etc.

-> exercise
    - power
    - factorial
    - productOfArray
    - recursiveRange
    - fib
    - reverse
    - isPalindrome
    - someRecursive
    - flatten
    - capitalizeFirst
    - nestedEvenSum
    - capitalizeWords
    - stringifyNumbers
    - collectStrings

## Searching Algorithms
# Linear Search
# Binary Search

## Sorting
# Bubble Sort
# Selection Sort
# Insertion Sort
# Merge Sort
# Quick Sort
# Radix Sort

## Linked List

# Single Linked List
-> Singly linked list is a linear data structure in which the elements are not stored in contiguous memory locations and each element is connected only to its next element using a pointer.

-> Basic Operations of Singly Linked List:
- Linked List Insertion
- Search an element in a Linked List (Iterative and Recursive)
- Find Length of a Linked List (Iterative and Recursive)
- Reverse a linked list
- Linked List Deletion (Deleting a given key)
- Linked List Deletion (Deleting a key at given position)
- Write a function to delete a Linked List

# Doubly Linked List
* A doubly linked list is a data structure that consists of a set of nodes, each of which contains a value and two pointers, one pointing to the previous node in the list and one pointing to the next node in the list. This allows for efficient traversal of the list in both directions, making it suitable for applications where frequent insertions and deletions are required.

-> Operations on Doubly Linked List
- Traversal in Doubly Linked List
- Searching in Doubly Linked List
- Finding Length of Doubly Linked List
- Insertion in Doubly Linked List:
    - Insertion at the beginning of Doubly Linked List
    - Insertion at the end of the Doubly Linked List
    - Insertion at a specific position in Doubly Linked List
- Deletion in Doubly Linked List:
    - Deletion of a node at the beginning of Doubly Linked List
    - Deletion of a node at the end of Doubly Linked List
    - Deletion of a node at a specific position in Doubly Linked List

# Circular Linked Lists
* A circular linked list is a special type of linked list where all the nodes are connected to form a circle. Unlike a regular linked list, which ends with a node pointing to NULL, the last node in a circular linked list points back to the first node. This means that you can keep traversing the list without ever reaching a NULL value.

-> Types of Circular Linked Lists
- Circular Singly Linked List
- Circular Doubly Linked List

-> Operations on the Circular Linked list
- Insertion
   - Insertion at the empty list
   - Insertion at the beginning
   - Insertion at the end
   - Insertion at the given position
- Deletion
   - Delete the first node
   - Delete the last node
   - Delete the node from any position
- Searching

## Stack
* A Stack is a linear data structure that follows a particular order in which the operations are performed. The order may be LIFO(Last In First Out) or FILO(First In Last Out). LIFO implies that the element that is inserted last, comes out first and FILO implies that the element that is inserted first, comes out last.

* It behaves like a stack of plates, where the last plate added is the first one to be removed. Think of it this way:
- Pushing an element onto the stack is like adding a new plate on top.
- Popping an element removes the top plate from the stack.

-> Exercise
- The Celebrity Problem
- Implement Queue using Stacks
- Implement two stacks in an array
- Implement Stack using Queues
- Stack using priority queue or heap
- Stack using single queue
- Infix to Postfix
- Prefix to Infix
- Prefix to Postfix
- Postfix to Prefix
- Postfix to Infix
- Infix To Prefix
- Check for balanced parentheses
- Arithmetic Expression Evalution
- Evaluation of Postfix Expression
- Reverse a stack using recursion
- Reverse Words
- Reverse a string using stack
- Reversing a Queue
- Reversing the first K of a Queue
- A Data Structure with O(1) Operations

## Queue
* A Queue Data Structure is a fundamental concept in computer science used for storing and managing data in a specific order. It follows the principle of "First in, First out" (FIFO), where the first element added to the queue is the first one to be removed. Queues are commonly used in various algorithms and applications for their simplicity and efficiency in managing data flow.

-> Exercise
- Implement Stack using Queues
- Detect cycle in an undirected graph using BFS
- Breadth First Search or BFS for a Graph
- Traversing directory in Java using BFS
- Vertical order traversal of Binary Tree using Map
- Print Right View of a Binary Tree
- Find Minimum Depth of a Binary Tree
- Check whether a given graph is Bipartite or not







