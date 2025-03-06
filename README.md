# BigInt-BIG-INTEGERS-Arbitrary Precision Integer Library
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







