# BigInt-BIG-INTEGERS-Arbitrary Precision Integer Library
In C/C++ the number of digits a long long int can have is a maximum of 20. And the question is to store the 22 digit number which is not easy to store in any kind of primitive type. So to deal with this type of problem let’s design a new data type which is going to be called BigInt In this article, a few basic operations are being implemented on the new data type.

Add two big integers.
Subtract two big integers
Multiply two big integers.
Divide two big integers.
Modulo two big integers
Raise a big integer to a power
The square root of a big integer
Comparison between two big integers to check which is greater and which is smaller.
Find the number of digits in the big integer.
Print the big integer.
Convert an integer to a big integer.
Applications Of BigInt:
Below are some basic applications of the new data type, BigInt:

Calculating the Fibonacci number of a large number.
Calculating the Catalan number of a large number
Calculating the Factorial of a big integer.
Approach:
To create a new data type of big integers following concepts are being implemented:

C++ strings in that we can store our numbers in the form of characters (in reverse order for efficiency purposes) such that using strings we can store very big numbers also.
For the addition/subtraction operation of two big integers, use the basic math for addition which says that add the corresponding two digits and if some carry is generated add it to the sum of the next digits and repeat this process until all digits are added/subtracted.
Similarly, for the multiplication of two numbers, use the basic mathematics approach which states that multiply every digit of one number with the other complete number and at last add all the numbers we get in multiplication.
The following operations are being performed on BigInt-
Defining some big integers.
Checking the number of digits in the big integer.
Post/Pre Incrementation or Decrementation
Adding two big integers.
Subtracting two big integers.
Multiplying two big integers.
Divide two big integers
Modulo of two big integers
The square root of a big integer (floor integer value)
Raise a big integer to a power
Converting a simple integer to a big integer.
Calculating Fibonacci up to 10 000. (even 100000 but slower)
Calculating Factorial up to 1 000.
Calculating Catalan up to 1 000.
Checking which big integer is greater and which is smaller.




## Overview
**BigInt** is a custom data type designed to handle large integers that exceed the storage capacity of primitive data types like `long long int` in C/C++. This implementation allows performing various arithmetic and mathematical operations on arbitrarily large integers.

## Features
- Supports large integer arithmetic (Addition, Subtraction, Multiplication, Division, Modulo)
- Exponentiation and Square Root operations
- Comparison between two BigInt numbers
- Conversion from standard integer types to BigInt
- Digit counting and printing functionalities
- Pre/Post Incrementation and Decrementation
- Efficient algorithms for factorial, Fibonacci, and Catalan number calculations

## Applications
BigInt can be used in:
- **Computational Mathematics**: Solving problems requiring large number arithmetic.
- **Cryptography**: Handling large numbers for encryption and decryption algorithms.
- **Scientific Computing**: Simulating large numerical computations.
- **Combinatorics**: Computing large factorials and Fibonacci numbers.

## Approach
- Uses **C++ strings** to store numbers as characters in reverse order for efficient computation.
- Addition and subtraction use digit-wise operations with carry handling.
- Multiplication follows basic mathematical principles for multi-digit numbers.
- Efficient division and modulo operations.
- Implements optimized algorithms for power calculations and square root.
- Provides operator overloading for seamless arithmetic operations.

## Supported Operations
- **Arithmetic Operations**:
  - Addition (`+`)
  - Subtraction (`-`)
  - Multiplication (`*`)
  - Division (`/`)
  - Modulo (`%`)
- **Mathematical Functions**:
  - Power (`^`)
  - Square Root (`sqrt()`)
- **Comparison Operators**:
  - Greater than (`>`)
  - Less than (`<`)
  - Equal to (`==`)
- **Utility Functions**:
  - Convert integer to BigInt
  - Find number of digits
  - Print the BigInt
- **Advanced Computations**:
  - Factorial calculation
  - Fibonacci sequence computation
  - Catalan number computation

## Usage Example
```cpp
#include "BigInt.h"
#include <iostream>

int main() {
    BigInt a = "123456789123456789";
    BigInt b = "987654321987654321";
    
    BigInt sum = a + b;
    BigInt product = a * b;
    
    std::cout << "Sum: " << sum << std::endl;
    std::cout << "Product: " << product << std::endl;
    
    return 0;
}
```

## Installation & Compilation
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/BigInt.git
   ```
2. Include `BigInt.h` and `BigInt.cpp` in your project.
3. Compile using a C++ compiler:
   ```sh
   g++ main.cpp BigInt.cpp -o bigint
   ```
4. Run the program:
   ```sh
   ./bigint
   ```

## Contributing
Feel free to contribute by improving the implementation or adding new features! Fork the repository and submit a pull request with your changes.

## License
This project is open-source and available under the **MIT License**.


