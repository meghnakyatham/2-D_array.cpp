# 2-D_array.cpp
**Matrix Addition Program**

This C++ program demonstrates matrix addition. Two matrices, A and B, are provided as input, and their corresponding elements are added to form a resulting matrix C. The program then displays the resulting matrix C.

**Usage:**

Compile the program using a C++ compiler, such as g++, and run the executable.


**Explanation:**

1. The program starts by including the necessary header files for input and output operations.

2. The `main()` function is the entry point of the program.

3. Matrices A and B are defined as two-dimensional arrays. Each array has 2 rows and 3 columns, and their values are provided in the initialization.

4. The matrix C is created to store the result of the addition of matrices A and B.

5. Nested loops are used to iterate over each element of matrices A and B. The corresponding elements are added and stored in the matrix C.

6. After performing matrix addition, another set of nested loops is used to display the elements of matrix C.

7. The program ends by returning 0 from the `main()` function, indicating successful execution.

**Note:**

You can compile the program using the following command:

```sh
g++ matrix_addition.cpp -o matrix_addition
```

And then run it:

```sh
./matrix_addition
```
