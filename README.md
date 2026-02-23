# Fast Algorithms for Solving Linear Systems with Structured Matrices

This project explores efficient algorithms for solving systems of linear equations involving structured matrices such as Toeplitz and Hankel matrices.

---

## 📌 Overview

In many scientific and engineering applications, solving large linear systems using traditional methods like Gaussian elimination is computationally expensive, requiring O(n³) time complexity.

This project implements two optimized approaches that exploit the special structure of Toeplitz and Hankel matrices:

- Levinson Recursion Algorithm
- FFT-Based Solver

These methods significantly reduce computational complexity while maintaining numerical accuracy.

---

## 🧠 Algorithms Implemented

### Levinson Recursion
- Recursive approach for solving Toeplitz systems
- Time Complexity: O(n²)
- Suitable for small to medium-sized structured systems

### FFT-Based Solver
- Embeds Toeplitz matrix into circulant matrix
- Uses Fast Fourier Transform (FFT)
- Time Complexity: O(n log n)
- Ideal for large-scale systems

---

## ⚙️ Implementation

Both algorithms were implemented using:

- Python
- NumPy
- SciPy

Randomly generated Toeplitz and Hankel matrices were used to benchmark performance and accuracy.

---

## 📊 Performance Comparison

Experimental results demonstrate that:

- Levinson Recursion provides efficient solutions for moderately sized systems
- FFT-Based Solver significantly outperforms traditional solvers for large matrix sizes

---

## 📄 Project Report

Full documentation available here:  
[Structured_Matrix_Solvers_Report.pdf](Structured_Matrix_Solvers_Report.pdf)

---

## 📈 Applications

- Signal Processing  
- Time Series Analysis  
- Numerical Linear Algebra  
- Image Reconstruction  
- Scientific Computing
