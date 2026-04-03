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




# 🧱 2. Basic Structure of a C Program

```c
#include <stdio.h>   // 🔗 Header file

int main() {         // 🚪 Entry point
    printf("Hello World");  // 🖨️ Output
    return 0;        // ✅ Exit
}


### **Breakdown of Basic Code:**
* **`#include`**: A file inclusion directive used to add header files.
* **`<stdio.h>`**: Standard Input Output header; allows functions like `printf()` and `scanf()`.
* **`int`**: A keyword for the integer data type (whole numbers).
* **`int main()`**: The entry point/starting point of the program.
* **`return 0;`**: Tells the OS the code ended without errors.


```

### 📝 Explanation

* `#include` → Adds libraries
* `main()` → Program starts here
* `printf()` → Displays output
* `return 0` → Successful execution

---

# 📊 3. Data Types

| 🔢 Type | 💡 Example |
| ------- | ---------- |
| int     | 10         |
| float   | 10.5       |
| char    | 'A'        |
| double  | 20.123     |

```c
int a = 10;
float b = 5.5;
char c = 'A';
```

---

# 🧾 4. Variables & Constants

### 🔹 Variable

```c
int age = 20;
```

### 🔸 Constant

```c
const float PI = 3.14;
```

---

# ➕ 5. Operators

### ⚙️ Types

* ➕ Arithmetic → `+ - * / %`
* 🔍 Relational → `== != > <`
* 🔗 Logical → `&& || !`

```c
int a = 5, b = 3;
printf("%d", a + b);
```

---

# ⌨️ 6. Input & Output

```c
int a;
scanf("%d", &a);              // ⌨️ Input
printf("Value: %d", a);       // 🖨️ Output
```

---

# 🔀 7. Control Statements

## 🔹 if-else

```c
if(a > 10){
    printf("Greater");
}else{
    printf("Smaller");
}
```

## 🔸 switch

```c

```c
switch(a){
    case 1: printf("One"); break;
    default: printf("Other");
}
```


## 🔁 Loops


### 🔹 for loop

```c
for(int i=0; i<5; i++){
    printf("%d", i);
}
```

### 🔸 while loop

```c
while(i < 5){
    i++;
}
---

# 🔁 8. Functions & Recursion

## 🧩 Function

```c
int add(int a, int b){
    return a + b;
}
```

## 📞 Function Call

```c
int result = add(2,3);
```

## 🔄 Recursion

```c
int fact(int n){
    if(n == 1) return 1;
    return n * fact(n-1);
}
```

---

# 🧠 9. Pointers (Core Concept)

```c
int a = 10;
int *p = &a;

printf("%d", *p);  // 📌 Value
printf("%p", p);   // 📍 Address
```

## 🔗 Pointer to Pointer

```c
int **pp = &p;
```

# 📦 10. Arrays & Strings

## 🔹 Array

```c
int arr[3] = {1,2,3};
```

## 🔸 String

```c
char name[] = "Hello";
```


## 🧰 String Functions

```c
#include <string.h>

