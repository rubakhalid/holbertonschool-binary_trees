## 📘 Learning Objectives & Key Definitions

### 🟩 What is a Binary Tree?
A **binary tree** is a hierarchical data structure in which each node has at most two children: a **left child** and a **right child**.

### 🟦 What is the Difference Between a Binary Tree and a Binary Search Tree (BST)?
- **Binary Tree:** Nodes have no specific order.
- **Binary Search Tree (BST):**
  - The left subtree contains only nodes with values **less than** the parent.
  - The right subtree contains only nodes with values **greater than** the parent.

### 🟨 What is the Possible Gain in Terms of Time Complexity Compared to Linked Lists?
- **Searching in a Linked List:** O(n)
- **Searching in a Balanced Binary Search Tree:** O(log n)  
→ Binary trees offer faster operations for searching, inserting, and deleting than linear structures.

### 🟧 What are the Depth, Height, and Size of a Binary Tree?
- **Depth:** The number of edges from a node to the root.
- **Height:** The number of edges from a node to the farthest leaf node below it.
- **Size:** The total number of nodes in the tree.

### 🟥 What are the Different Tree Traversal Methods?
1. **Pre-order:** Visit node → Left → Right  
2. **In-order:** Left → Visit node → Right  
3. **Post-order:** Left → Right → Visit node

### 🟪 What is a Complete, Full, Perfect, and Balanced Binary Tree?
- **Complete Tree:** All levels are fully filled except possibly the last, which is filled from left to right.
- **Full Tree:** Every node has either 0 or 2 children.
- **Perfect Tree:** All interior nodes have exactly 2 children, and all leaves are at the same level.
- **Balanced Tree:** The height difference between the left and right subtrees of every node is no more than 1.

