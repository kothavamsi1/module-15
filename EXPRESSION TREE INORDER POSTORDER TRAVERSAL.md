# Experiment 9(c): Expression Tree – Inorder and Postorder Traversal

## Aim
To write a Python program to build the following expression tree and print the inorder and postorder traversal.


---

## Algorithm

1. Begin the program.
2. Import the necessary modules (`build`, `Node`) from the `binarytree` package.
3. Define a list `x` representing the binary tree in pre-order format.
4. Use the `build()` function to construct the expression tree from the list.
5. Print the inorder traversal of the expression tree using `.inorder`.
6. Print the postorder traversal of the expression tree using `.postorder`.
7. End the program.

---

## Program

```python

from binarytree import build,Node
x=['*','+','-',9,3,8,4]
t=build(x)
print(t.inorder)
print(t.postorder)

```

## OUTPUT
![431411125-b14c5387-3397-44b6-a9f5-4aaaa56899eb](https://github.com/user-attachments/assets/529ecf36-2f5e-4c39-b164-a03c7eae2e5c)




## RESULT
Thus the program succesffuly completed the Build an Expression Tree and Print Inorder and Postorder Traversals and executrd successfully.
