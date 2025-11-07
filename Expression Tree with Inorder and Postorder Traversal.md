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
from binarytree import build
s=['*','+','-',9,3,8,4]
t=build(s)
print(t.inorder)
print(t.postorder)
```

## OUTPUT
<img width="1706" height="234" alt="Screenshot 2025-11-07 094205" src="https://github.com/user-attachments/assets/a63fd0d7-e8c4-4059-ab9c-616932184885" />

```

## RESULT
Thus the Python program to build the given expression tree and print the inorder and postorder traversals is executed successfully.
