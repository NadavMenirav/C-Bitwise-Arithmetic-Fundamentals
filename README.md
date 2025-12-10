# ⚙️ C Bitwise & Arithmetic Fundamentals

A foundational project implemented in C that explores low-level data representation and manipulation. This program demonstrates proficiency in converting between number bases (binary, decimal, hexadecimal) and manipulating individual bits using bitwise operations.

## ✨ Technical Concepts Demonstrated

This project is a strong demonstration of core computer science principles implemented directly in C:

* **Bitwise Operations ($\text{XOR}$, $\text{Shift}$, $\text{AND}$):** Explicit use of bitwise operators (`^`, `>>`, `&`) to perform operations at the bit level .
* **Number System Conversion:** Implementation of logic to convert a number from an arbitrary base (2-9) into its decimal equivalent (Base-n to Base-10).
* **Data Representation:** Handling and parsing input in various bases (Binary, Hexadecimal, Decimal) using C's `scanf` functions (`%c`, `%x`, `%d`).
* **Character Arithmetic:** Utilizing ASCII values (`'0'` is 48) to convert character inputs to numeric values for calculation.

---

## 🛠️ Key Exercises

### 1. Binary XOR Calculation
Performs the Bitwise XOR operation ($\text{A} \oplus \text{B}$) on two 4-digit binary inputs.

### 2. Hexadecimal Arithmetic & Bit Extraction
Calculates the sum of two hexadecimal numbers and then extracts and displays the 4 least significant bits of the result using right-shift and bitwise $\text{AND}$ operators.

### 3. Base-n to Decimal Conversion
Converts a 5-digit number from any base between 2 and 9 to its decimal (Base-10) equivalent using the positional numeral system formula:
$$\text{Decimal} = \sum_{i=0}^{k-1} d_i \times \text{Base}^i$$

### 4. Bit Value Extraction
Determines the value (0 or 1) of a specific bit position in a given integer.

---

## 🚀 Running the Program

This project requires a standard C compiler (like GCC).

1.  **Compile:**
    ```bash
    gcc -o ex_1 main.c
    ```
2.  **Execute:**
    ```bash
    ./ex_1
    ```
    *The program will prompt the user for input for each exercise sequentially.*
