# NumPy Day 2 Assignment

## Tasks:

### 1. Array Slicing Practice
Create a 2D array with the following matrix:
```
[[10, 20, 30, 40],
 [50, 60, 70, 80],
 [90, 100, 110, 120]]
```

Perform the following slicing operations:
- Extract the first two rows
- Extract the last two columns
- Extract the center 2×2 block (values 60, 70, 100, 110)
- Reverse all rows
- Use boolean indexing to extract all values greater than 60

### 2. Array Operations and Broadcasting
Given two arrays:
```python
a = np.array([[1, 2, 3],
              [4, 5, 6]])

b = np.array([10, 20, 30])
```

Perform the following operations:
- Add array `b` to each row of array `a` using broadcasting
- Multiply array `a` by 2
- Calculate the mean, sum, and standard deviation of array `a`
- Find the maximum value in each column of array `a`
- Find the minimum value in each row of array `a`
- Compare which elements in array `a` are greater than 3 (use comparison operators)
