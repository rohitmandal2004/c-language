# c-language
### **Operators in C and Their Practical Examples**  

Operators in C are symbols that perform operations on variables and values. They are categorized into different types:  

---

## **1. Arithmetic Operators**  
Used for mathematical operations.  

| Operator | Description  | Example (`a = 10, b = 5`) |
|----------|-------------|---------------------------|
| `+`  | Addition  | `a + b` → `15` |
| `-`  | Subtraction  | `a - b` → `5` |
| `*`  | Multiplication  | `a * b` → `50` |
| `/`  | Division  | `a / b` → `2` |
| `%`  | Modulus (Remainder) | `a % b` → `0` |

**Example:**
```c
#include <stdio.h>
int main() {
    int a = 10, b = 5;
    printf("Addition: %d\n", a + b);
    printf("Subtraction: %d\n", a - b);
    printf("Multiplication: %d\n", a * b);
    printf("Division: %d\n", a / b);
    printf("Modulus: %d\n", a % b);
    return 0;
}
```

---

## **2. Relational (Comparison) Operators**  
Used to compare values, returning **1 (true)** or **0 (false)**.  

| Operator | Description | Example (`a = 10, b = 5`) |
|----------|------------|---------------------------|
| `==`  | Equal to | `a == b` → `0` (false) |
| `!=`  | Not equal to | `a != b` → `1` (true) |
| `>`  | Greater than | `a > b` → `1` (true) |
| `<`  | Less than | `a < b` → `0` (false) |
| `>=`  | Greater than or equal to | `a >= b` → `1` |
| `<=`  | Less than or equal to | `a <= b` → `0` |

**Example:**
```c
#include <stdio.h>
int main() {
    int a = 10, b = 5;
    if (a > b) {
        printf("%d is greater than %d\n", a, b);
    }
    return 0;
}
```

---

## **3. Logical Operators**  
Used for logical operations, returning **1 (true)** or **0 (false)**.  

| Operator | Description | Example (`a = 1, b = 0`) |
|----------|------------|---------------------------|
| `&&` | Logical AND | `a && b` → `0` (false) |
| `||` | Logical OR | `a || b` → `1` (true) |
| `!` | Logical NOT | `!a` → `0`, `!b` → `1` |

**Example:**
```c
#include <stdio.h>
int main() {
    int a = 1, b = 0;
    if (a && b) 
        printf("Both are true\n");
    else 
        printf("One or both are false\n");
    return 0;
}
```

---

## **4. Bitwise Operators**  
Perform operations at the bit level.  

| Operator | Description | Example (`a = 5 (0101)`, `b = 3 (0011)`) |
|----------|------------|---------------------------|
| `&`  | Bitwise AND | `a & b` → `1` (0001) |
| `|`  | Bitwise OR | `a | b` → `7` (0111) |
| `^`  | Bitwise XOR | `a ^ b` → `6` (0110) |
| `~`  | Bitwise NOT | `~a` → `-6` (in 2's complement) |
| `<<` | Left shift | `a << 1` → `10` (1010) |
| `>>` | Right shift | `a >> 1` → `2` (0010) |

**Example:**
```c
#include <stdio.h>
int main() {
    int a = 5, b = 3;
    printf("Bitwise AND: %d\n", a & b);
    printf("Bitwise OR: %d\n", a | b);
    printf("Bitwise XOR: %d\n", a ^ b);
    printf("Left Shift: %d\n", a << 1);
    printf("Right Shift: %d\n", a >> 1);
    return 0;
}
```

---

## **5. Assignment Operators**  
Used to assign values to variables.  

| Operator | Example (`a = 10, b = 5`) | Equivalent To |
|----------|---------------------------|--------------|
| `=`  | `a = b` | `a = 5` |
| `+=` | `a += b` | `a = a + b` |
| `-=` | `a -= b` | `a = a - b` |
| `*=` | `a *= b` | `a = a * b` |
| `/=` | `a /= b` | `a = a / b` |
| `%=` | `a %= b` | `a = a % b` |

**Example:**
```c
#include <stdio.h>
int main() {
    int a = 10, b = 5;
    a += b; // a = a + b
    printf("New value of a: %d\n", a);
    return 0;
}
```

---

## **6. Increment and Decrement Operators**  
Used to increase or decrease the value of a variable.  

| Operator | Description | Example (`a = 10`) |
|----------|------------|---------------------------|
| `++` | Increment | `a++` → `11` |
| `--` | Decrement | `a--` → `9` |

**Example:**
```c
#include <stdio.h>
int main() {
    int a = 10;
    printf("Post-increment: %d\n", a++); // Prints 10, then a becomes 11
    printf("Pre-increment: %d\n", ++a); // a becomes 12, then prints 12
    return 0;
}
```

---

## **7. Ternary Operator (`? :`)**  
A shorthand for `if-else`.  

**Syntax:**
```c
condition ? expression1 : expression2;
```

**Example:**
```c
#include <stdio.h>
int main() {
    int a = 10, b = 5;
    int max = (a > b) ? a : b;
    printf("Maximum is: %d\n", max);
    return 0;
}
```

---

## **8. Sizeof Operator**  
Returns the size of a data type or variable in bytes.  

**Example:**
```c
#include <stdio.h>
int main() {
    printf("Size of int: %lu bytes\n", sizeof(int));
    printf("Size of double: %lu bytes\n", sizeof(double));
    return 0;
}
```

---

### **Conclusion**  
Operators are essential in C programming to perform computations, comparisons, logical operations, and bit manipulations. Mastering them will help in writing efficient programs.

Let me know if you need more details or explanations! 🚀
