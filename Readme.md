## A Practical Guide to Parallel Computing in Macroeconomics

This repository contains the source code referenced in the paper *A Practical Guide to Parallel Computing in Macroeconomics* by Jesús
Fernández-Villaverde and David Zarruk Valencia.

### Abstract from the paper

> Parallel computing opens the door to solving and estimating richer models in Economics. From dynamic optimization
> problems with high dimensionality to structural estimation with complex data, readily-available and economical parallel
> computing allows researchers to tackle problems in Economics that were beyond the realm of possibility just a decade ago. This
> paper describes the basics of parallel computing for economists, reviews widely-used implementation routines in `Julia`, `Python`,
> `R`, `Matlab`, `C++` (`OpenMP` and `MPI`) and `CUDA` and compares performance gains using as a test bed a standard life-cycle problem
> such as those used in macro, labor, and other fields.

The file `Makefile` contains the compilation flags used in Linux and can be used to execute the codes in every language.

## Files

1. `Cpp_main.cpp`: C++ code for OpenMP
2. `CUDA_main.cu`: CUDA code
3. `Julia_main_parallel.jl`: Julia code
4. `Julia_main_pmap.jl`: Julia code
5. `Matlab_main.m`: Matlab code
6. `MPI_host_file`: MPI host file
6. `MPI_main.cpp`: C++ code for MPI
8. `Python_main.py`: Python code
9. `Rcpp_main.cpp`: C++ code for Rcpp package in R
10. `Rcpp_main.R`: Rcpp code
11. `R_main.R`: R code
12. `Makefile`: Makefile to execute codes
