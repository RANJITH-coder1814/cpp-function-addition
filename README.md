# C++ Function Addition Program

This repository contains a simple C++ program that demonstrates the use of a **user-defined function** to add two numbers.

## 📌 Program Description
- Uses a separate function `add()` to calculate the sum of two integers.
- Demonstrates function calling from `main()`.
- Prints the result using standard output.

## 💻 Source Code

```cpp
#include<iostream>
using namespace std;

int add(int x, int y) {
    int z;
    z = x + y;
    return z;
}

int main() {
    int a = 10, b = 5, c;
    c = add(a, b);
    cout << "Sum is " << c;
    return 0;
}
