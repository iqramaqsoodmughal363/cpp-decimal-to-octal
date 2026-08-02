# 🔢 Decimal to Octal Converter in C++

> A C++ program that converts a decimal (base-10) integer into its octal (base-8) equivalent using an array-based iterative division method.

---

## 📋 Overview

This program demonstrates the conversion of a decimal number to its octal representation. The octal number system uses digits `0` through `7`.

The program uses an integer array to store the octal digits and employs an iterative division method to compute the result.

---

## 🧮 Program Logic & Execution Flow

1. The user enters a decimal integer.
2. The program initializes an integer array `oct[50]` to store the octal digits, starting with index `i = 0`.
3. A `while` loop performs successive division by 8:
   - `oct[i++] = temp % 8` calculates the remainder and stores it in the array, then increments the index.
   - `temp = temp / 8` updates the quotient for the next iteration.
4. The loop continues until the quotient becomes `0`.
5. The program then prints the array elements from the last stored index `(i-1)` down to `0` to display the correct octal sequence.

---

## 💻 Sample Input / Output

**Input:**
Enter a decimal number : 100


**Output:**
Octal equivalent of 100 is : 144


**Input:**
Enter a decimal number : 8


**Output:**
Octal equivalent of 8 is : 10


---

## 🛠️ How to Compile and Run (Windows & Linux)

### 🪟 For Windows Users
| Step | Command |
| :---: | :--- |
| **Compile** | `g++ decimal_to_octal.cpp -o decimal_to_octal.exe` |
| **Run** | `decimal_to_octal.exe` |

### 🐧 For Linux / macOS Users
| Step | Command |
| :---: | :--- |
| **Compile** | `g++ decimal_to_octal.cpp -o decimal_to_octal` |
| **Run** | `./decimal_to_octal` |

---

## 📂 Project Structure
cpp-decimal-to-octal/
│
├── decimal_to_octal.cpp # Main source code file
└── README.md # Project documentation (this file)


---

## 👩‍💻 Author

**Iqra Maqsood Mughal**  
*C++ Developer | Programming Enthusiast*

---

## 📅 Date

**August 2, 2026**

---

## 📄 License

This project is open-source and intended for educational purposes.
