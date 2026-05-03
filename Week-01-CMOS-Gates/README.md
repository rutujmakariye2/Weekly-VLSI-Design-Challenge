# Week 1: CMOS Basic Gates (NAND & XOR)

## 🔹 Objective
To design and implement CMOS basic gates using Microwind with Euler path optimization.

---

## 🔹 Theory

### 🔸 CMOS NAND Gate
The NAND gate uses:
- PMOS in parallel
- NMOS in series

Output is LOW only when both inputs are HIGH.

---

### 🔸 CMOS XOR Gate
The XOR gate outputs HIGH when inputs are different.

It requires a more complex transistor arrangement compared to basic gates.

---

## 🔹 Euler Path Optimization
Used to:
- Reduce diffusion breaks
- Optimize layout area
- Improve design efficiency

---

## 🔹 Implementation
- Designed NAND and XOR gates at layout level
- Applied Euler path for transistor ordering
- Implemented layouts in Microwind
- Generated .msk files

---

## 🔹 Truth Tables

### NAND Gate
A | B | Y
0 | 0 | 1
0 | 1 | 1
1 | 0 | 1
1 | 1 | 0

### XOR Gate
A | B | Y
0 | 0 | 0
0 | 1 | 1
1 | 0 | 1
1 | 1 | 0

---

## 🔹 Tools Used
- Microwind

---

## 🔹 Files Included
- Layout images
- Output waveforms
- .msk files

---

## 🔹 Conclusion
Successfully designed CMOS NAND and XOR gates using Microwind with optimized layout.
