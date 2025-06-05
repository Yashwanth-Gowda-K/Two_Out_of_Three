# Two_Out_of_Three

Problem Description
Given three integer arrays nums1, nums2, and nums3, return a distinct array containing all values that appear in at least two of the three arrays.

Example
Input: nums1 = [1,1,3,2], nums2 = [2,3], nums3 = [3]
Output: [3,2]

Explanation: 
- 3 appears in all three arrays
- 2 appears in nums1 and nums2
- 
Solution Approaches
1. Hash Set Counting (Optimal)
Time Complexity: O(n₁ + n₂ + n₃)
Space Complexity: O(n₁ + n₂ + n₃)

Approach:
Convert each array to a set to remove duplicates
Count occurrences of each number across all sets
Return numbers appearing in ≥2 sets

2. Set Operations (One-Liner)
Time Complexity: O(n₁ + n₂ + n₃)
Space Complexity: O(n₁ + n₂ + n₃)
