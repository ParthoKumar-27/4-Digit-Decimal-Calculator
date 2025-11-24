# 4-Digit-Decimal-Calculator
A complete and professional digital logic design of a **4-Digit Decimal Calculator**, built and simulated in **Logisim / Logisim Evolution**.  
The calculator accepts two 4-digit decimal operands (each digit encoded in **4-bit BCD**), performs **addition** or **subtraction**, and displays the final result on a four-digit seven-segment display system.

---

## 📌 Overview

This project demonstrates the full design workflow of a multi-digit digital arithmetic system.  
The calculator operates on two 4-digit decimal numbers and supports:

- ➕ **Addition**  
- ➖ **Subtraction** (via **two’s complement** arithmetic)


The project highlights correct bus routing, splitter usage, control logic, and structured datapath design.

---

## 🎯 Features

- ✔ **Supports two 4-digit decimal numbers** (each digit = 4-bit BCD)
- ✔ **Addition & Subtraction** modes  
  - `0` → Addition  
  - `1` → Subtraction (two’s complement)
- ✔ **Seven-segment display output** (BCD decoded)
- ✔ Ideal for **Digital Logic Design (DLD)** courses and demonstrations

---

## ▶️ How to Run This Project in Logisim

### ✔ Requirements
- Java Runtime Environment (JRE)
- Logisim  
- or **Logisim Evolution (recommended)** — version **3.7+**

---

### ✔ Steps to Run

1. **Download or extract the project folder.**  
   - JRE
   - Logisim
   - The CalculatorCircuit.circ file

2. **Open Logisim and Load the circuit file:**
    - Go to **File → Open**
    - Select:  
      ```
      CalculatorCircuit.circ
      ```

3. **View the Top-Level Circuit**  
  You will see all main components:
    - Input DIP switches  
    - Operation selector  
    - Register datapath  
    - Seven-segment display modules  

4. **Enter Input Values**
    - Use DIP switches to set each 4-bit BCD digit   

5. **Choose the Operation**
    - Set the selector switch to:
      - `0` → Addition  
      - `1` → Subtraction  

6. **Observe Output**
    - The result is displayed across **four seven-segment displays**

7. **Reset**
    - Use the reset pin/button to clear all registers and flags  

---

## 👤 Contributors

| Name                     |
|--------------------------|
| Partho Kumar Mondal      |
| Shahriar Hossain Thesun  | 
| Md. Irfan Iqbal          | 

---

