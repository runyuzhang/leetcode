# Find leaves in binary tree

Given a binary tree, collect a tree's nodes as if you were doing this: Collect and remove all leaves, repeat until the tree is empty.

```
          1
         / \
        2   3
       / \     
      4   5  
```

This tree would yield \[4, 5, 3\], \[2\], \[1\]



Main Idea: 

* Sub-problem: ordered leaves in the subtree, zip the ordered leaves from left tree and right tree, and then append the root



