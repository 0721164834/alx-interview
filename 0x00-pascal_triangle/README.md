# Pascal's Triangle

## Description
This project contains a Python function `pascal_triangle(n)` that generates the Pascal's triangle of a given size `n`. Pascal's triangle is a triangular array of binomial coefficients. 

Each number in the triangle is the sum of the two numbers directly above it. The first and last elements of each row are always 1.

## Usage
The function returns a list of lists, where each inner list represents a row in Pascal's triangle.

### Function Signature:
```python
def pascal_triangle(n):
    """
    Returns a list of lists representing Pascal's triangle of size n.
    - Returns an empty list if n <= 0.
    - Assumes n is always a positive integer.
    """

