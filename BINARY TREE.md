# Experiment 9(a): Binary Tree (Float Values)

## Aim
To write a Python program to build a binary tree with a root, left, and right node using float values.

---

## Algorithm

1. Start the program.
2. Import the `Node` class from the `binarytree` module.
3. Create a root node using the `Node` class and input a floating-point value for the root.
4. Create left and right child nodes for the root using floating-point values.
5. Convert the binary tree to a list.
6. Print the list of nodes.
7. End the program.

---

## Program

```python
class Node:
    def __init__(self, value):
        self.value = value
        self.left = None
        self.right = None

# Step 1: Get float inputs from the user
values = []
for i in range(3):
    val = float(input(f"Enter value {i+1} (float): "))
    values.append(val)

# Step 2: Build the binary tree
root = Node(values[0])
root.left = Node(values[1])
root.right = Node(values[2])

# Step 3: Print the list of node values
print("List of node values in the binary tree:", values)

```

## OUTPUT

![431408316-1b82011c-1dda-4392-b4c6-1b24197ca709](https://github.com/user-attachments/assets/97a4c67f-a4aa-4150-bcd7-6b31254436b8)



## RESULT
The program accepts three float values from the user, builds a binary tree with those values, and prints the list of node values.
