Given an array of size N containing only 0s, 1s, and 2s; sort the array in ascending order.
You must solve this problem without using the library's sort function.

### Input Format

The first line contains an integer n the length of the original array a
The second line contains n integers a1, a2, ... the array elements themselves.

### Output Format

Print corresponding sorted array elements.

### Example 1:
```txt
Input:
    5
    0 2 1 2 0
Output:
    0 0 1 2 2
Explanation:
    0s 1s and 2s are segregated into ascending order.
```

### Example 2:
```txt
Input:
    3
    0 1 0
Output:
    0 0 1
Explanation:
    0s 1s and 2s are segregated into ascending order.
```

#### Constraints:
- 1 <= N <= 1000000
- 0 <= A[i] <= 2
- Expected Time Complexity: O(N)
- Expected Auxiliary Space: O(1)