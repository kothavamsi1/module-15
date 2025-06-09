# Experiment 9(d): Heap Tree

## Aim
To write a Python program to build a heap tree using appropriate Python package and function.

---

## Algorithm

1. Start the program.
2. Import the `heapq` module.
3. Define a function `heaptree()` that takes a list `H` as input.
4. Use `heapq.heapify(H)` to convert the list into a valid heap (min-heap).
5. Print the created heap.
6. End the program.

---

## Program

```python
from binarytree import heap,build,Node
def heaptree(L):
  x=L
  t=build(x)
  for i in t.values:
    print(i,"-->",end='')
  print("\nHeight : ",t.height)
  print("Is min heap? : ",t.is_min_heap)
  print("Is complete tree? : ",t.is_complete)
```

## OUTPUT

![431412488-12625415-aec9-4cf2-ac70-e72d313f8a49](https://github.com/user-attachments/assets/e778e75b-7b9f-4bd6-bbc5-cb05c33aed31)



## RESULT
thus the task has been completed To Build Binary Tree and Check Min Heap, Completeness, and Height and successfully verified
