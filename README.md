# Building and Printing a Binary Tree

## 📌 Aim
To write a Python program that builds a **binary tree** with a **root**, **left**, and **right** node using the **Node function** from the `binarytree` library. The values for the nodes are obtained from the user and stored in a list.

---

## 🛠 Procedure
1. Import the `Node` class from the `binarytree` library.
2. Initialize an empty list to store node values.
3. Take inputs from the user and append them to the list.
4. Create a binary tree with a root node and left and right child nodes.
5. Print the node values using an appropriate method.

---

## 💻 Program

```python
from binarytree import Node

# Initialize an empty list to store node values
l = []

# Get values from the user and append to the list
for i in range(0, 3):
    a = input()
    l.append(a)

# Create the root and child nodes of the binary tree
root = Node(l[0])
root.left = Node(l[1])
root.right = Node(l[2])

# Print the binary tree node values
print("Binary Tree :")
for i in root.values:
    print(i, "--> ", end='')
```
---
## Output 

![image](https://github.com/user-attachments/assets/318dc9f0-7287-453a-b66b-4f661bcdfe56)

## Result 

Thus, the program was successfully created and executed to print the binary tree.

