# Week 3: Full Adder Design Comparison (CMOS vs Hybrid Approach)

## 🔹 Objective
To design a 1-bit Full Adder using two different approaches and compare their outputs and performance:
1. Standard CMOS Full Adder
2. CMOS + Pseudo-NMOS based Hybrid Design

---

## 🔹 Theory
A Full Adder adds three inputs: A, B, and Cin  
Outputs:
- Sum (S)
- Carry-out (Cout)

---

## 🔹 Design Approaches

### 🔸 1. Standard CMOS Full Adder
- Entire circuit implemented using complementary CMOS logic
- Provides strong logic levels
- Higher transistor count

### 🔸 2. Hybrid Design (CMOS + Pseudo-NMOS)
- Carry (Cout) implemented using Pseudo-NMOS logic
- Sum implemented using CMOS logic
- Optimized for area and transistor reduction

---

## 🔹 Key Observation

Both designs were simulated and compared.

✔ CMOS design → better signal integrity  
✔ Hybrid design → reduced area and transistor count  

---

## 🔹 Issue & Fix
Initial mismatch in output was due to incorrect signal routing between Carry and Sum blocks.

✔ Fixed by correcting internal connections  
✔ Verified both designs independently  

---

## 🔹 Truth Table

A | B | Cin | Sum | Cout
--|---|-----|-----|-----
0 | 0 |  0  |  0  |  0
0 | 0 |  1  |  1  |  0
0 | 1 |  0  |  1  |  0
0 | 1 |  1  |  0  |  1
1 | 0 |  0  |  1  |  0
1 | 0 |  1  |  0  |  1
1 | 1 |  0  |  0  |  1
1 | 1 |  1  |  1  |  1

---

## 🔹 Results Included
- CMOS Full Adder output waveform
- Hybrid Full Adder output waveform
- Layout images for both designs

---

## 🔹 Tools Used
- Microwind
- DSCH

---

## 🔹 Conclusion
This experiment helped compare full CMOS implementation with hybrid optimization, highlighting trade-offs between performance, area, and design complexity.
