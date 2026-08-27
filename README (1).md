# Practical 1: Sorting Algorithms

This practical implements Selection Sort, Bubble Sort, and Merge Sort, insertion sort, quick sort 
Each algorithm includes implementation, time complexity analysis (best, worst, and average cases), and execution time measurement.

# Practical 2: Linear Search

This practical implements the Linear Search algorithm with interactive user input.
It demonstrates:
- Implementation of linear search that returns the index of the target (or -1 if not found).
- Measurement of execution time using `time.perf_counter()`.
- Time complexity analysis (Best, Average, Worst cases).

Usage:
- Interactive: run the script and follow prompts to provide the list and target value.
- Demo: run the script with a demo flag (if provided in the script).
1. linear search 
2. binary search

PRACTICAL 3 : Min-Heap and Max-Heap Sort

Description:

This project implements Heap Sort in Python using heapq.

Min-Heap: Sorts elements in ascending order. Max-Heap: Sorts elements in descending order. Features Takes user input for array elements. Uses heapq.heapify() and heapq.heappop(). Measures execution time using time.perf_counter(). Displays time complexity. Example

Min-Heap:

Input: 25, 14, 36, 85, 96 Output: [14, 25, 36, 85, 96]

Max-Heap:

Input: 25, 78, 89, 45, 56, 33 Output: [89, 78, 56, 45, 33, 25] Complexity Best Case: O(n log n) Average Case: O(n log n) Worst Case: O(n log n) Space Complexity: O(n) Requirements Python 3 heapq and time modules (built-in) Conclusion

The program demonstrates how Min-Heap and Max-Heap can be used to efficiently sort an array in ascending and descending order.


Practical-4:Factorial of ieterative and recursive function

In this practical, we learned how to find the factorial of a number using two different methods: iterative and recursive. In the iterative method, we use a loop to multiply the numbers from 1 to the given number. In the recursive method, the function calls itself with a smaller value until it reaches the base condition. Both methods give the same factorial result, but they work in different ways.

CONCLUSION:

From this practical, we understood the difference between iterative and recursive approaches for solving a problem. Both methods are useful for calculating factorials, and this practical helped us understand how loops and recursion can be used to solve the same problem. CONCLUSION:

From this practical, we understood the difference between iterative and recursive approaches for solving a problem. Both methods are useful for calculating factorials, and this practical helped us understand how loops and recursion can be used to solve the same problem.

SUMAMRY OF PRACT-7:

The Coin Change Problem is solved using Dynamic Programming to find the minimum number of coins needed to make a given amount. The program takes the number of coins, coin values, and target amount as input from the user. It creates a dynamic programming table where each position stores the minimum number of coins required to form that particular amount. The program checks all available coins and updates the table with the best possible solution. If the amount cannot be formed using the given coins, the program returns -1. The algorithm has a time complexity of O(n × amount) and a space complexity of O(amount).

CONCULSION:

Dynamic Programming makes the Coin Change Problem easier and faster to solve. The program gives the minimum number of coins or returns -1 if the amount cannot be made.
