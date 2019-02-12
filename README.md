# Binary-Search
Binary search using java script

Binary search is a sort using divide and conquer. It used to search any element in a sorted array. As compared to linear, binary search is much faster with Time Complexity of O(logN) whereas linear search algorithm works in O(N) time complexity.
Here I am using binary search in Javascript using both iterative and recursive ways. 

Recursive Approach :

1. BASE CONDITION: If starting index is greater than ending index return false.
2. Compute the middle index.
3. Compare the middle element with number x. If equal return true.
4. If greater, call the same function with ending index = middle-1 and repeat step 1.
5. If smaller, call the same function with starting index = middle+1 and repeat step 1.

Iterative Approach:

In iterative approach instead of recursion, we will use a while loop and the loop will run until it hits the base condition i.e start becomes greater than end.
