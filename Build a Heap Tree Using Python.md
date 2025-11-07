# Ex. No: 15D - Build a Heap Tree Using Python

## AIM:
To write a Python program to build a heap tree using appropriate Python package and function.

---

## ALGORITHM:

1. **Start the program.**
2. Import the `heapq` module.
3. Define a function `heaptree(H)` that takes a list `H` as input.
4. Use `heapq.heapify(H)` to convert the list into a min-heap.
5. Print the created heap.
6. **End the program.**

---

## PROGRAM:

```
import heapq
H=[10,15,30,40,50,100,40]
heapq.heapify(H)
print("The created heap is : ",H)
a=int(input())
heapq.heappush(H,a)
print("Heap after Insertion : ",H)
```

## OUTPUT

<img width="1405" height="264" alt="Screenshot 2025-11-07 093621" src="https://github.com/user-attachments/assets/326c90f8-811a-482c-b94e-915c1756b5f7" />

```

## RESULT
Thus the Python program to build a heap tree using appropriate Python package and function is executed successfully.
