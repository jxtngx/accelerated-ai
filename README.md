# Accelerated Artificial Intelligence

This project introduces concepts of high performance computing (HPC) for artificial intelligence (AI) by leveraging C++ and Python.

Primary goals of the repo are:

1. to design and implement a simple CUDA/C++ kernel
2. to design and implement Python bindings for that kernel
3. to use the Python interface and test against benchmarks

Accomplishing these goals will aid in understanding the code bases of CuPy and PyTorch, along with enabling next-steps in more advanced techniques.

Secondary goals of the repo are:

1. to introduce Python interfaces for CUDA kernels
2. to introduce multi-language design concepts
2. to introduce multi-language code quality concepts

Accomplishing these goals will aid in preparing to contribute to CuPy and PyTorch, and other such libraries which use CUDA/C++ and Python.

In summary, the general goal of the repo is to create a C++ and Python program for an AI application, while adhering to software engineering best practices.

## Requisite background

While not required, a basic understanding of C++ and Python will be useful to understand the syntax and control flow of both programming languages.

## Supporting materials and inspiration

1. Mathematics for Machine Learning, by Deisenroth et al
2. Programming Massively Parallel Processors, by Hwu et al
3. Python docs
4. CUDA docs
5. PyTorch code base
6. CuPy code base
7. [An Even Easier Introduction to CUDA](https://developer.nvidia.com/blog/even-easier-introduction-cuda/), by Mark Harris
8. [How to Optimize a CUDA Matmul Kernel](https://siboehm.com/articles/22/CUDA-MMM), by Simon Boehm