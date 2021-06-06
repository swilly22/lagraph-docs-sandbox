# LAGraph documentation test

## BFS algorithm

$$
f=(startVertex) = T
$$

$$
level = 1\; to \; n-1
$$

$$
s \langle f \rangle = level
$$

$$
f \langle \neg s \rangle = fA
$$

## Some code

```c
GrB_mxm(&frontier, numsp, GrB_NULL, Int32AddMul, A, frontier, desc_tsr);
```

