### Numpy Splitting

array a:

```
array([[0, 1, 2],
      [3, 4, 5],
      [6, 7, 8]])
```

* hsplit(): Splitting the array through horizontal axis

```
# first parameter: array, second parameter: number of parts.
In: np.hsplit(a, 3)
Out:
[array([[0],
        [3],
        [6]]),
 array([[1],
        [4],
        [7]]),
 array([[2],
        [5],
        [8]])]
```

* vsplit(): Splitting the array through vertical axis.

```
# first parameter: array, second parameter: number of parts
In: np.bsplit(a, 3)
Out: 
[array([[0, 1, 2]]), 
 array([[3, 4, 5]]),
 array([[6, 7, 8]])]
```

* dsplit(): Splitting the array through deepth.

```
c = np.arrange(27).reshape(3, 3, 3)

In: np.dsplit(c, 3)
Out:
[array([[[0],
        [3],
        [6]],
        [[9],
        [12],
        [15]],
        [[18],
        [21],
        [24]]]),
 array([[[1],
        [4],
        [7]],
        [[10],
        [13],
        [16]],
        [[19],
        [22],
        [25]]]),
 array([[[2],
        [5],
        [8]],
        [[11],
        [14],
        [17]],
        [[20],
        [23],
        [26]]])]
```

* split(): if parameter axis = 1, it's equal to hsplit(); if parameter axis = 0, it's equal to vsplit().

---

