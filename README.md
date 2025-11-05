# ⚙️ Assembly Language Program Collection (8086 MASM)

Welcome to my **Assembly Language Code Repository**!  
This repository contains a collection of **8086 Assembly Language programs** written for **low-level computation, data manipulation, and algorithmic operations**.  
Each file represents a core concept in **microprocessor programming**, demonstrating how fundamental arithmetic, logic, and control operations are performed directly with CPU instructions.

These codes were developed as part of **Microprocessor and Assembly Language Laboratory coursework** during my **Computer Science and Engineering** studies.

---

## 🧠 Topics and Implementations

### 🔢 Arithmetic Operations
1. **Add, Subtract, Multiply, and Divide**  
   📄 `Add Sub Mul Div.asm`  
   ➤ Demonstrates basic arithmetic operations using registers and accumulator.

2. **16-bit Multiplication**  
   📄 `16bit multiplication.asm`  
   ➤ Performs signed/unsigned 16-bit multiplication using the `MUL` instruction.

---

### 🧮 Logical and Comparative Operations
1. **Maximum Number from Array**  
   📄 `Maximum number from array.asm`  
   ➤ Iterates through an array to find and display the largest number.

2. **Minimum Number from Array**  
   📄 `Minimum number from array.asm`  
   ➤ Finds and displays the smallest number stored in an array.

---

### 🔠 String Manipulation
1. **Copy a String**  
   📄 `Copy a String.asm`  
   ➤ Copies characters from one string to another using `MOVSB`.

2. **Reverse a String**  
   📄 `Reverse a String.asm`  
   ➤ Reverses a string by manipulating memory pointers and registers.

---

### 🔢 Number Evaluation
1. **Prime Number Check (Fixed Input)**  
   📄 `Prime or Not.asm`  
   ➤ Determines whether a given number is prime.

2. **Prime Number Check (Keyboard Input)**  
   📄 `Prime or Not from keyboard.asm`  
   ➤ Accepts user input and checks primality dynamically.

---

### 💾 Data Conversion
1. **Unpacked BCD Conversion**  
   📄 `Unpacked BCD.asm`  
   ➤ Converts binary values to **Unpacked BCD (Binary-Coded Decimal)** representation for display.

---

## 🧰 Tools and Environment

- **Assembler:** MASM / TASM  
- **Processor:** Intel 8086 Architecture  
- **Platform:** DOSBox / EMU8086 / Turbo Assembler  
- **Key Concepts:** Registers, Flags, Stack Operations, Loops, Interrupts

---

## 🎯 Learning Objectives

Through this collection, learners will:
- Understand **register-level data handling** and **addressing modes**.  
- Develop insights into **low-level algorithm implementation**.  
- Gain experience in **assembly debugging and flow control**.  
- Strengthen knowledge of **computer architecture fundamentals**.

---

## 🚀 How to Run

1. Open any `.asm` file using **MASM** or **EMU8086**.  
2. Assemble and run the program using:
   ```bash
   masm filename.asm
   link filename.obj
   filename.exe
