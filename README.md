# matrix-program
This C++ program performs addition, subtraction, and multiplication of two square matrices (up to 10x10) using a menu-driven approach. The user enters the matrix size and elements, then selects an operation from the menu. Based on the choice, the program calculates and displays the result. The loop continues until the user selects "Exit".
# 🧮 Matrix Operations in C++

## 📌 Overview
This C++ program performs **Addition**, **Subtraction**, and **Multiplication** on two **square matrices** using a **menu-driven approach**. It continuously allows the user to select an operation until they choose to exit.

---

## 💡 Features
- Accepts two square matrices of size up to 10x10.
- Provides a simple menu for:
  - Matrix Addition
  - Matrix Subtraction
  - Matrix Multiplication
  - Exit
- Displays the result matrix in a clean format.
- Validates user input for menu choice.

---

## 🔧 How It Works

1. **Input Phase**:
   - User enters the size `n` of the square matrices.
   - User inputs the elements of **Matrix A** and **Matrix B**.

2. **Menu Loop**:
   - Repeatedly displays options:
     ```
     1. Addition
     2. Subtraction
     3. Multiplication
     4. Exit
     ```
   - Based on the selected option, it performs the desired operation and prints the result.

3. **Matrix Operations**:
   - **Addition**: `C[i][j] = A[i][j] + B[i][j]`
   - **Subtraction**: `C[i][j] = A[i][j] - B[i][j]`
   - **Multiplication**: Uses nested loops to compute each element of result matrix C.

4. **Exit Option**:
   - Program ends when the user selects option `4`.

---

## 🖥️ Sample Output
Enter size of square matrices (max 10): 2
Enter elements of first matrix:
1 2
3 4
Enter elements of second matrix:
5 6
7 8

Menu:

Addition

Subtraction

Multiplication

Exit
Enter your choice: 1
Result of Addition:
[ 6 8 ]
[ 10 12 ]

