# 2-Dimensional-Array
## Aim:
### To study and implement operations using two-dimensional arrays in C++, including input/output, summation, multiplication, and traversal techniques.
## Theory:
🔹 Multidimensional Arrays
A 2D array is an array of arrays, often used to represent matrices. It is declared as:
datatype arrayName[rows][columns];


### Matrix Operations
- Input & Display: Accept matrix elements from the user and display them in matrix form.
- Addition: Possible only when both matrices have the same dimensions.
- Multiplication: Valid when the number of columns in the first matrix equals the number of rows in the second.
- Diagonal Addition:
- Primary Diagonal: Elements where row index = column index.
- Secondary Diagonal: Elements where row index + column index = size - 1.
- Transpose: Converts rows into columns and vice versa.
- Row Comparison: Compares elements of the first row with the second row for equality or difference.

### Tools Required
- Software: Any C++ compiler (e.g., Turbo C++, Code::Blocks, Dev C++, or online compilers like Replit or GeeksforGeeks IDE)
- Hardware: Computer system with basic configuration
- Language: C++
## Algoritm:
### 1. Take Matrix Input from User and Display It
Algorithm:
- Start
- Declare a 2D array matrix[r][c]
- For each row i from 0 to r-1
- For each column j from 0 to c-1
- Prompt user to input matrix[i][j]
- For each row i from 0 to r-1
- For each column j from 0 to c-1
- Display matrix[i][j]
- End
###  2. Addition of Two Matrices
Algorithm:
- Start
- Input dimensions r and c
- Declare matrices A[r][c], B[r][c], and Sum[r][c]
- Input elements of matrix A and B
- For each i from 0 to r-1
- For each j from 0 to c-1
- Sum[i][j] = A[i][j] + B[i][j]
- Display matrix Sum
- End


### 3. Diagonal Addition
Algorithm:
- Start
- Input dimension n (for square matrix)
- Declare matrix M[n][n]
- Input elements of matrix M
- Initialize primarySum = 0, secondarySum = 0
- For each i from 0 to n-1
- primarySum += M[i][i]
- secondarySum += M[i][n-1-i]
- Display primarySum and secondarySum
- End

### 4. Multiplication of Two Matrices
Algorithm:
- Start
- Input dimensions r1, c1 for matrix A and r2, c2 for matrix B
- Check if c1 == r2, else exit
- Declare matrices A[r1][c1], B[r2][c2], and Product[r1][c2]
- Input elements of matrix A and B
- For each i from 0 to r1-1
- For each j from 0 to c2-1
- Initialize Product[i][j] = 0
- For each k from 0 to c1-1
- Product[i][j] += A[i][k] * B[k][j]
- Display matrix Product
- End
  ## Conclusion:
 ### This experiment helped us understand and implement basic matrix operations using 2D arrays in C++. We performed input/output, addition, multiplication, diagonal sums, transpose, and row comparisons. It strengthened our grasp of array handling, nested loops, and logical conditions in C++.






