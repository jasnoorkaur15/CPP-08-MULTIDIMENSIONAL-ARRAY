# Experiment 8 – Study and Implementation of 2D Arrays in C++

## Aim  
To study the concept of two-dimensional arrays in C++ and implement fundamental operations on matrices.

---

## Objectives  
- Understand declaration, initialization, and traversal of 2D arrays.  
- Perform basic matrix operations:  
  - Displaying the matrix  
  - Matrix addition  
  - Matrix multiplication  
  - Diagonal sum  
  - Matrix transpose  
- Apply nested loops for multi-dimensional data processing.  
- Strengthen problem-solving skills with tabular/matrix-based data.  
- Relate mathematical concepts of matrices with C++ programming.  

---

## Theory  

### 1. Definition of a 2D Array  
A two-dimensional array is a structured collection of elements arranged in rows and columns, stored in contiguous memory locations. It can be visualized as a matrix or a table.  

```cpp
int matrix[3][3] = {
    {1, 2, 3},
    {4, 5, 6},
    {7, 8, 9}
};
```

Here, `matrix[0][0] = 1` and `matrix[2][1] = 8`.

---

### 2. Memory Representation

In C++, 2D arrays are stored in **row-major order**:

* All elements of the first row are stored together in memory.
* Then all elements of the second row, and so on.

---

### 3. Declaration & Initialization

**Static Declaration:**

```cpp
int arr[2][3]; // 2 rows, 3 columns
```

**Initialization:**

```cpp
int arr[2][3] = { {1,2,3}, {4,5,6} };
```

**Partial Initialization:**

```cpp
int arr[2][3] = { {1}, {4,5} }; // Remaining elements set to 0
```

---

### 4. Operations on 2D Arrays

#### A. Displaying a Matrix  
Input taken using nested loops and printed in matrix form.  

#### B. Matrix Addition  
* Condition: Dimensions must be equal (m × n).  
* Formula: `C[i][j] = A[i][j] + B[i][j]`  

#### C. Matrix Multiplication  
* Condition: If A is m × n and B is n × p, result will be m × p.  
* Requires triple nested loops.  

#### D. Diagonal Addition  
* **Primary diagonal:** Elements where `i == j`.  
* **Secondary diagonal:** Elements where `i + j == n - 1`.  

#### E. Transpose of a Matrix  
* Definition: Interchanging rows and columns.  
* Used in mathematics, graphics, and image processing.  

---

### 5. Advantages of 2D Arrays
- Organizes data in matrix form.  
- Useful in image processing, scientific computing, and data analysis.  
- Efficient for mathematical computations.  

---

### 6. Limitations of 2D Arrays
- Fixed size (static allocation).  
- Memory wastage if unused elements exist.  
- Insertion/deletion operations are costly.  

---

## Program Descriptions

### 1. Matrix Display  
Reads elements into a 2D array using nested loops and prints them in a matrix format.  

### 2. Matrix Addition  
Takes two matrices of equal dimensions and adds their corresponding elements to produce a result matrix.  

### 3. Matrix Multiplication  
Performs multiplication of two compatible matrices using triple nested loops and stores the result.  

### 4. Diagonal Sum  
Finds the sum of elements along both primary (`i == j`) and secondary (`i + j == n - 1`) diagonals.  

### 5. Matrix Transpose  
Generates the transpose of a matrix by interchanging rows and columns.  

---

## Concepts Used
- Nested Loops  
- Conditional Statements  
- Array Traversal  
- Index-based Access  

---

## Conclusion  
Through this experiment, the concept of **2D arrays in C++** was studied and implemented successfully. Various matrix operations such as **display, addition, multiplication, diagonal sum, and transpose** were carried out using nested loops and array traversal techniques. The experiment highlights the importance of arrays in handling tabular/matrix-based data and their applications in mathematics, graphics, and computing.



