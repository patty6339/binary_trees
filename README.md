# binary_trees

This repo contains files for the project above. 

### What is a Binary Tree?

A binary tree is a data structure in which each node has at most two children, referred to as the left child and the right child. This hierarchical structure is used for various purposes, such as organizing data for quick search, insertion, and deletion.

### Difference Between a Binary Tree and a Binary Search Tree (BST)

- **Binary Tree**: A general structure where each node has up to two children.
- **Binary Search Tree (BST)**: A special type of binary tree where:
  - The left subtree of a node contains only nodes with keys less than the node's key.
  - The right subtree of a node contains only nodes with keys greater than the node's key.
  - Both the left and right subtrees must also be binary search trees.

### Possible Gain in Terms of Time Complexity Compared to Linked Lists

- **Search, Insertion, Deletion**:
  - **Linked List**: O(n)
  - **Binary Search Tree**: O(h), where h is the height of the tree. In a balanced BST, this can be as good as O(log n), where n is the number of nodes.

### Depth, Height, and Size of a Binary Tree

- **Depth of a Node**: The number of edges from the root node to the node.
- **Height of a Node**: The number of edges on the longest path from the node to a leaf. The height of a tree is the height of the root node.
- **Size of a Tree**: The total number of nodes in the tree.

### Traversal Methods to Go Through a Binary Tree

1. **In-Order Traversal (LNR)**: Left, Node, Right
2. **Pre-Order Traversal (NLR)**: Node, Left, Right
3. **Post-Order Traversal (LRN)**: Left, Right, Node
4. **Level-Order Traversal**: Nodes are visited level by level from left to right.

### Types of Binary Trees

- **Complete Binary Tree**: All levels are completely filled except possibly the last level, which is filled from left to right.
- **Full Binary Tree**: Every node has either 0 or 2 children.
- **Perfect Binary Tree**: All internal nodes have two children, and all leaves are at the same level.
- **Balanced Binary Tree**: The difference between the heights of the left and right subtrees for every node is not more than 1.

These properties are often used to describe and analyze the structure and efficiency of binary trees in various applications.