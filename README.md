# Binary Search Tree (Python Example)

This is a Python implementation of a Binary Search Tree (BST) that allows you to perform the following operations:

1. Add an element to the tree.
2. Search for an element in the tree.
3. Remove an element from the tree.
4. Visualize the tree using the `TreePrint` script.

## Logic Behind Binary Search Trees (BSTs)
A Binary Search Tree is a data structure that maintains the following property for each node:

The left subtree of a node contains only nodes with values less than the node's value.
The right subtree of a node contains only nodes with values greater than the node's value.
Both left and right subtrees are also Binary Search Trees.
This property allows for efficient searching, insertion, and removal of elements, making it an essential data structure for sorted data. When performing these operations, we can traverse the tree using the property's comparison logic to efficiently find the desired element or position for insertion/removal.

The Binary Search Tree is implemented using nodes, where each node contains a value and references to its left and right children. The root node is the topmost node of the tree, from which we can traverse the entire tree.
