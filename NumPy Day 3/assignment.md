# NumPy Day 3 Assignment

## Tasks:

### 1. Array Manipulation and Transformation
Given the following 2D array:
```python
data = np.array([[12, 5, 8, 15],
                 [3, 18, 9, 6],
                 [14, 7, 11, 20]])
```

Perform the following operations:
- **a)** Transpose the array and print the result
- **b)** Flatten the array using both `ravel()` and `flatten()`, then modify the first element of each result. Explain the difference in behavior.
- **c)** Reshape the array to shape (6, 2)
- **d)** Create two separate arrays by splitting the original array vertically
- **e)** Use `np.where()` to replace all values less than 10 with 0, and all other values with their square
- **f)** Create a masked array that masks all values greater than 15
- **g)** Concatenate the original array with its transpose (hint: you'll need to reshape first to match dimensions)

### 2. Image Filter Application using NumPy Arrays
Load an image (you can use any image file or create a sample image array) and apply the any filters (eg., Grayscale, blur, negative, brightness) using NumPy operations.
