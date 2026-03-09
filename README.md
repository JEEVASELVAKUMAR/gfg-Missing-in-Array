# Missing Number in Array (Java)

## Problem
Given an array `arr` of size `n-1` containing distinct integers from the range `1` to `n`, one number is missing from the sequence. The task is to find and return the missing number.

## Example 1
Input:
arr = [1,2,3,5]

Output:
4

Explanation:
Numbers from 1 to 5 should be present, but 4 is missing.

## Example 2
Input:
arr = [8,2,4,5,3,7,1]

Output:
6

Explanation:
Numbers from 1 to 8 should be present, but 6 is missing.

## Approach
1. Calculate `n` as `arr.length + 1`.
2. Find the expected sum of numbers from `1` to `n` using the formula:
   
   n(n+1)/2

3. Calculate the sum of all elements in the array.
4. Subtract the array sum from the expected sum to get the missing number.

## Time Complexity
O(n) – The array is traversed once.

## Space Complexity
O(1) – No extra space is used.

## Language
Java
