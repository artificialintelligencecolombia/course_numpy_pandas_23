NumPy is a powerful Python library for numerical computing. While it would be exhaustive to list every function and tool in NumPy, below is a fundamental list of some of its most commonly used functions, tools, and features, along with a brief description and tips for each:

1. **Array Creation**:
    - `numpy.array()`: Creates an array from a list or tuple.
      * Tip: Ensure that all elements are of the same data type for performance.
      * Values:
        - `numpy.array([1, 2, 3])`: 1-dimensional array.
        - `numpy.array([[1, 2], [3, 4]])`: 2-dimensional array.

2. **Basic Operations**:
    - Arithmetic operators (`+`, `-`, `*`, `/`, `**`): Work element-wise on arrays.
      * Tip: Use `numpy.dot()` for matrix multiplication.
    
3. **Special Arrays**:
    - `numpy.zeros()`: Returns a new array of given shape and type, filled with zeros.
    - `numpy.ones()`: Returns a new array of given shape and type, filled with ones.
    - `numpy.eye()`: Returns a 2-D array with ones on the diagonal and zeros elsewhere.
      * Tip: Useful for initializing arrays quickly.
    
4. **Array Attributes**:
    - `.shape`: Returns the dimensions of the array.
    - `.dtype`: Returns the data type of the array.
      * Tip: Choose the appropriate data type (`float32`, `int64`, etc.) to save memory and enhance performance.
    
5. **Indexing and Slicing**:
    - Use square brackets `[]` to index and slice arrays.
      * Tip: Remember that Python indexing starts from 0. Slicing follows the format `[start:stop:step]`.
    
6. **Math Functions**:
    - `numpy.sin()`, `numpy.cos()`, `numpy.tan()`: Trigonometric functions.
    - `numpy.exp()`: Exponential function.
    - `numpy.log()`: Natural logarithm.
      * Tip: Use these to apply mathematical operations element-wise to arrays.
    
7. **Aggregation Functions**:
    - `numpy.sum()`: Sum of all the elements.
    - `numpy.mean()`: Mean of the array.
    - `numpy.median()`: Median value.
    - `numpy.std()`: Standard deviation.
      * Tip: Use the `axis` argument to apply these functions along a specific dimension.
    
8. **Reshaping and Resizing**:
    - `numpy.reshape()`: Gives a new shape to an array without changing its data.
    - `numpy.resize()`: Returns a new array with the specified shape.
      * Tip: Ensure that the total number of elements remains constant when reshaping.
    
9. **Linear Algebra**:
    - `numpy.linalg.inv()`: Compute the inverse of a matrix.
    - `numpy.linalg.eig()`: Compute the eigenvalues and eigenvectors.
      * Tip: Ensure matrices are square and of appropriate dimensions before applying these operations.
    
10. **Random Number Generation**:
    - `numpy.random.rand()`: Returns random values in a given shape.
    - `numpy.random.randn()`: Returns samples from the “standard normal” distribution.
      * Tip: Seed the random generator with `numpy.random.seed()` for reproducibility.
    
11. **File Input and Output**:
    - `numpy.loadtxt()`: Load data from a text file.
    - `numpy.savetxt()`: Save data to a text file.
      * Tip: Use `delimiter` argument to specify separators (e.g., comma for CSV files).
    
12. **Broadcasting**:
    - Powerful mechanism that allows NumPy to work with arrays of different shapes when performing arithmetic operations.
      * Tip: Understand the broadcasting rules to avoid shape mismatches.

13. **Stacking**:
    - `numpy.hstack()`: Stack arrays horizontally.
    - `numpy.vstack()`: Stack arrays vertically.
      * Tip: Ensure that arrays have matching shapes along the respective dimensions.

14. **Boolean Masking**:
    - Use boolean conditions to filter arrays.
      * Tip: Combine multiple conditions using `&` (and), `|` (or), and `~` (not).

This list is by no means exhaustive, but it does cover many of the fundamental tools and functions provided by NumPy. Always refer to the official NumPy documentation for detailed information and examples.