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

