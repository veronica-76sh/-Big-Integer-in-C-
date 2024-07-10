 This README provides a comprehensive guide to understanding, building, and using  BigInt library.

 # BigIntCPP

A C++ library for handling large integers (big integers) with support for various arithmetic and comparison operations.

## Features

- Addition, subtraction, multiplication, and division of large integers.
- Comparison operations (less than, greater than, equal to, etc.).
- Input and output operations.

## Getting Started

### Prerequisites

- C++17 or higher
- CMake 3.10 or higher

### Building the Project

1. Clone the repository:

```bash
git clone https://github.com/yourusername/BigIntCPP.git
cd BigIntCPP


2.Create a build directory and run CMake:

mkdir build
cd build
cmake ..

3.Build the project:
make


Running the Examples
./example

Running the Tests
./test_bigint

Usage
#include "BigInt.h"

int main() {
    BigInt a("12345678901234567890");
    BigInt b("98765432109876543210");

    BigInt c = a + b;
    BigInt d = b - a;
    BigInt e = a * b;
    BigInt f = b / a;

    std::cout << "a + b = " << c << std::endl;
    std::cout << "b - a = " << d << std::endl;
    std::cout << "a * b = " << e << std::endl;
    std::cout << "b / a = " << f << std::endl;

    return 0;
}

Project Structure

BigIntCPP/
├── CMakeLists.txt
├── README.md
├── include/
│   └── BigInt.h
├── src/
│   └── BigInt.cpp
├── tests/
│   └── test_bigint.cpp
└── examples/
    └── example_usage.cpp




