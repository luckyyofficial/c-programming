# Comprehensive C Programming Notes

A complete guide covering C language fundamentals, from basic structure to advanced control flow.

---

## 1. Introduction to C
C is a **versatile** (adaptable) and **powerful** programming language that allows developers to create efficient and portable software. It is known for its **close-to-hardware** capabilities, making it suitable for systems programming and embedded systems.

### How to use C
1.  **Write Code:** Use a text editor. A basic program involves defining functions, such as `main()`.
2.  **Compile:** Use a compiler (like **GCC**) to convert C code into machine-readable binary code.
3.  **Run Program:** Execute the compiled file in the terminal.

### Main Uses of C
* Creating Operating Systems (Windows, Linux, etc.)
* Developing Embedded Systems (Microchips, IoT)
* Writing Device Drivers
* Building high-performance applications and game engines.

---

## 2. Basic Structure (Default Code)
Every C program follows this fundamental template:

```c
#include <stdio.h> // Pre-processor directive for Input/Output

int main() { 
    // Code starts executing here
    printf("Hello World");
    return 0; // Indicates successful completion
}

### **Breakdown of Basic Code:**
* **`#include`**: A file inclusion directive used to add header files.
* **`<stdio.h>`**: Standard Input Output header; allows functions like `printf()` and `scanf()`.
* **`int`**: A keyword for the integer data type (whole numbers).
* **`int main()`**: The entry point/starting point of the program.
* **`return 0;`**: Tells the OS the code ended without errors.