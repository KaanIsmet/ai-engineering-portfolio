# C++ Matrix Library

A lightweight, header-only C++ matrix library providing essential linear algebra operations for scientific computing and machine learning applications.

## Features

- **Header-only implementation** - Simple single-file integration
- **Core matrix operations** - Addition, subtraction, multiplication, transpose
- **Linear algebra utilities** - Determinant, inverse, decompositions
- **Template-based design** - Support for different numeric types
- **Zero external dependencies** - Pure C++ implementation

## Installation

Simply include the header file in your project:
```cpp
#include "matrix.hpp"
```

## Requirements

- C++11 or higher
- Standard C++ compiler (g++, clang++, MSVC)

## Usage

### Basic Operations
```cpp
#include "matrix.hpp"

// Create matrices
Matrix A(3, 3);
Matrix B(3, 3);

// Matrix multiplication
Matrix C = A * B;

// Matrix addition
Matrix D = A + B;

// Zero
A = A.zero();
```

### Compilation
```bash
g++ -std=c++11 your_program.cpp -o your_program
```

## Performance

Designed for clarity and correctness with opportunities for optimization. Suitable for:
- Educational purposes
- Prototyping ML algorithms
- Small to medium-scale computations

## Applications

This library serves as a foundation for:
- Neural network implementations from scratch
- Linear regression and machine learning algorithms
- Scientific computing projects
- Understanding low-level matrix operations

## Future Enhancements

- GPU acceleration with ROCm/HIP
- SIMD optimization
- Parallel processing support
- Advanced decompositions (SVD, QR, Cholesky)
