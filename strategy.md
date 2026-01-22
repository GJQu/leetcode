## 1. Two Pointers
****When:**** You’re working with a sorted array, linked list, or string, and need to compare or find pairs/subarrays.

****
**Core idea:**
Keep two indices (left, right) and move them toward each other (or through the array) depending on conditions.

**Example problems:**
* 1. Two Sum II (sorted array)
* 125. Valid Palindrome
* 167. Two Sum II
* 11. Container With Most Water
* 283. Move Zeroes
 
## 2. Sliding Window
****When:**** You’re looking for a contiguous subarray or substring that satisfies some condition (sum, length, etc.).

****
**Core idea:**
Maintain a window (left, right) and expand/shrink it dynamically.

**Example problems:**
* 3. Longest Substring Without Repeating Characters
* 76. Minimum Window Substring
* 209. Minimum Size Subarray Sum
* 438. Find All Anagrams in a String
 
## 3. Binary Tree DFS / BFS
****When:**** The problem involves traversing a tree or graph.

****
**Core idea:**
Use recursion (DFS) or a queue (BFS). Learn to:
* Return something from recursion (height, sum, etc.)
* Update something global (diameter, path sum)

**Example problems:**
* 104. Maximum Depth of Binary Tree
* 543. Diameter of Binary Tree
* 102. Binary Tree Level Order Traversal
* 112. Path Sum
* 226. Invert Binary Tree
 
## 4. Binary Search
**When:** The input is sorted or the problem can be reframed as “find the first/last/threshold.”

**Core idea:**
Use the mid-point and decide which half to keep searching.

**Example problems:**
* 704. Binary Search
* 35. Search Insert Position
* 153. Find Minimum in Rotated Sorted Array
* 34. Find First and Last Position of Element
 
## 5. Recursion + Backtracking
**When:** You need to explore all possible combinations, subsets, or paths.

**Core idea:**
DFS that “chooses / unchooses” options recursively.

**Example problems:**
* 46. Permutations
* 78. Subsets
* 39. Combination Sum
* 17. Letter Combinations of a Phone Number
* 22. Generate Parentheses
 
## 6. Dynamic Programming (DP)
**When:** You see overlapping subproblems or “optimal” wording (“min,” “max,” “ways”).

**Core idea:**
Break the problem into subproblems and reuse results (top-down with memoization or bottom-up with a table).

**Example problems:**
* 70. Climbing Stairs
* 198. House Robber
* 53. Maximum Subarray
* 62. Unique Paths
* 300. Longest Increasing Subsequence
 
## 7. Greedy
**When:** Each local best choice leads to a global optimum (and you can prove it).

**Core idea:**
Sort or use a priority structure, always pick the best next step.

**Example problems:**
* 455. Assign Cookies
* 435. Non-overlapping Intervals
* 452. Minimum Number of Arrows to Burst Balloons
* 122. Best Time to Buy and Sell Stock II
 
## 8. Hashing / Counting
**When:** You need to store seen elements, frequencies, or detect duplicates efficiently.

**Core idea:**
Use dictionaries (hashmaps) or sets for O(1) lookups.

**Example problems:**
* 1. Two Sum
* 242. Valid Anagram
* 347. Top K Frequent Elements
* 219. Contains Duplicate II
 
## 9. Linked List Manipulation
**When:** You’re asked to reverse, merge, or detect cycles.

**Core idea:**
Use slow/fast pointers, dummy heads, and pointer re-linking.

**Example problems:**
* 206. Reverse Linked List
* 21. Merge Two Sorted Lists
* 141. Linked List Cycle
* 19. Remove Nth Node From End
 
## 10. Graph Traversal (DFS/BFS/Union-Find)
**When:** You’re asked about connectivity, paths, or islands.

**Core idea:**
Use adjacency lists or grids, traverse all reachable nodes.

**Example problems:**
* 200. Number of Islands
* 133. Clone Graph
* 323. Number of Connected Components
* 207. Course Schedule
 
**Pro tip:** How to practice patterns effectively

1.	Pick one pattern.
2.	Do 3–5 problems of increasing difficulty.
3.	Summarize the steps in your own words.
4.	Review after a week to see if you remember the logic.
