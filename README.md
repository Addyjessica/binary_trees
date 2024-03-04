A binary tree is a hierarchical data structure that is composed of nodes. Each node in a binary tree has at most two children, referred to as the left child and the right child. The structure of a binary tree makes it suitable for a variety of applications, including searching, sorting, and hierarchical representation of data.
Terminology

    Node: The fundamental building block of a binary tree. It contains data and references to its left and right children.

    Root: The topmost node in a binary tree. It serves as the entry point for accessing the tree's structure.

    Leaf: A node with no children, i.e., both its left and right child references are null.

    Parent: A node in a binary tree with at least one child.

    Child: A node in a binary tree referenced by another node.

    Subtree: A binary tree formed by a node and all its descendants.

Types of Binary Trees

    Full Binary Tree:
        Every node has 0 or 2 children.
        No nodes have only one child.

    Complete Binary Tree:
        All levels, except possibly the last, are completely filled.
        Nodes are filled from left to right.

    Perfect Binary Tree:
        All interior nodes have two children.
        All leaves are at the same level.

    Balanced Binary Tree:
        The height of the left and right subtrees of any node differs by at most one.

Common Operations

    Insertion:
        Adding a new node to the tree while maintaining the binary tree properties.

    Deletion:
        Removing a node from the tree while preserving the binary tree structure.

    Traversal:
        Visiting and processing all nodes in the tree in a specific order.
            Inorder: Left, Root, Right
            Preorder: Root, Left, Right
            Postorder: Left, Right, Root

    Searching:
        Locating a specific node in the binary tree.