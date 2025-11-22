# Ex. No: 15C - Expression Tree with Inorder and Postorder Traversal

## AIM:
To write a Python program to build the given expression tree and print the inorder and postorder traversals.

---

## ALGORITHM:

1. **Start the program.**
2. Import the required modules (`build` and `Node` from `binarytree`).
3. Define a list `x` representing the expression tree in pre-order fashion (with `None` for missing nodes).
4. Use the `build()` function to generate the binary tree.
5. Print the **inorder** and **postorder** traversal of the tree.
6. **End the program.**

---

## PROGRAM:

```
from binarytree import build,Node
x=['*','+','-',9,3,8,4]
t=build(x)
print(t.inorder)
print(t.postorder)
```

## OUTPUT
<img width="1090" height="153" alt="image" src="https://github.com/user-attachments/assets/707b0abb-f121-46ea-af57-6fbbaf2ff775" />


## RESULT
  Thus the program to build the given expression tree and print the inorder and postorder traversals is successively verified.
