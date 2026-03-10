
# Merge Sort Implementation in Python

This project demonstrates the implementation of the **Merge Sort algorithm**, a highly efficient sorting technique based on the **Divide and Conquer** paradigm. The algorithm recursively divides the input array into smaller subarrays, sorts them, and merges them back together to produce a fully sorted array.

## Problem Statement

Given an array of integers, sort the array in **ascending order** using the **Merge Sort algorithm**.  
The sorted array should **not be returned**, but instead the sorted result should be stored directly inside the input array `data`.

## Constraints

-5 × 10⁴ ≤ data[i] ≤ 5 × 10⁴

## Example

### Sample Input 1
-23, -40, 10, 5, -9, 0, 1


### Sample Output 1
[-40, -23, -9, 0, 1, 5, 10]


### Sample Input 2
5, 1, 1, 2, 0, 0

### Sample Output 2
[0, 0, 1, 1, 2, 5]



## How Merge Sort Works

1. Divide the array into two halves.
2. Recursively sort both halves.
3. Merge the sorted halves into a single sorted array.

This process continues until the entire array becomes sorted.

## Time Complexity

| Case | Complexity |
|-----|------------|
| Best Case | O(n log n) |
| Average Case | O(n log n) |
| Worst Case | O(n log n) |

## Space Complexity

O(n) due to the temporary arrays used during merging.

## Technologies Used

- Python
- Data Structures
- Recursion
- Divide and Conquer Algorithm
