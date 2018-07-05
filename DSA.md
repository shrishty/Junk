## Junk DSA Questions

### Burning tree

There is a **binary tree (n-aray)** tree. Input will be root and any random node called **x**. 
starting from x all the adjacent nodes (including parent and child) will take **one sec** to burn. This fire will get propagated to further nodes and finally whole tree will get burnt. 
Find the time the tree will take to burn completely.

**Ans**: Distance between the node x and the farthest node.

### Count number of possible strings

A string consists of `0` `1` and `?`. `?` can be 0 or `1`. Count the number of all possible string.
Eg. For 10?001, the number of possible strings are 100001 and 101001. So the output will be 2

**Ans**: 2^n where n is number of `?`s in the string

### Remove Duplicated lines

Given a file remove all the duplicated lines. What if the file is very large.

**Ans**: 
* [Bloom Filters](https://stackoverflow.com/questions/3751969/fastest-way-to-remove-duplicate-lines-in-very-large-txt-files)
* [Hashing](https://stackoverflow.com/questions/2467353/memory-efficient-way-to-remove-duplicate-lines-in-a-text-file-using-c)


### Minimum swaps required to bring all elements less than or equal to k together

Given an array of n positive integers and a number k. Find the minimum number of swaps required to bring all the numbers less than or equal to k together.
eg: {4,1,2,7,5,3} if k=3 then 1 swap is enough.

**Ans**: https://www.geeksforgeeks.org/minimum-swaps-required-bring-elements-less-equal-k-together/

### Find the first circular tour that visits all petrol pumps

Suppose there is a circle. There are n petrol pumps on that circle. You are given two sets of data.

1. The amount of petrol that every petrol pump has.
2. Distance from that petrol pump to the next petrol pump.

Calculate the first point from where a truck will be able to complete the circle (The truck will stop at each petrol pump and it has infinite capacity). Expected time complexity is O(n). Assume for 1 litre petrol, the truck can go 1 unit of distance.

For example, let there be 4 petrol pumps with amount of petrol and distance to next petrol pump value pairs as {4, 6}, {6, 5}, {7, 3} and {4, 5}. The first point from where truck can make a circular tour is 2nd petrol pump. Output should be “start = 1” (index of 2nd petrol pump).

**Ans**: https://www.geeksforgeeks.org/find-a-tour-that-visits-all-stations/

### Count ways to reach the n’th stair

There are n stairs, a person standing at the bottom wants to reach the top. The person can climb either 1 stair or 2 stairs at a time. Count the number of ways, the person can reach the top.
Ex: Input: n = 1
Output: 1
There is only one way to climb 1 stair

Input: n = 2
Output: 2
There are two ways: (1, 1) and (2)

Input: n = 4
Output: 5
(1, 1, 1, 1), (1, 1, 2), (2, 1, 1), (1, 2, 1), (2, 2)

**Ans**: https://www.geeksforgeeks.org/count-ways-reach-nth-stair/
