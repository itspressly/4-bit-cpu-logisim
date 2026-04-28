# 4-bit-cpu-logisim
Custom 4-bit CPU with RAM, ALU, and instruction-based control built in Logisim

# 4-bit CPU with RAM (Logisim)

## 🚀 Overview

This project is a custom-designed 4-bit CPU built in Logisim, implementing core computer architecture concepts such as instruction execution, memory interaction, and clocked state updates.

## ⚙️ Features

* 4-bit ALU (ADD, AND, OR)
* Program Counter (PC)
* ROM-based instruction control
* RAM with read/write capability
* Accumulator (CPU State Register)
* MUX-based data path control
* Clock-driven execution

## 🧠 Architecture

The CPU follows a simplified execution cycle:

PC → ROM → Control Signals → ALU → Register → RAM

## 💾 Memory Behavior

* RAM stores values only when Write Enable (LD) is active
* Data written comes from the CPU State Register (Q)
* Memory updates occur on clock edges

## 📊 Dashboard View

A visual dashboard was created to monitor:

* Instruction execution
* ALU inputs/outputs
* RAM address and stored values
* Write Enable signal

## 📸 Screenshots

 <img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/80f5d027-de09-4179-bfb4-3ffb57a5453f" />

* while live
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/d52b4ebd-d958-4f1a-b70c-1487b6107c18" />

## 🎥 Demo


## 🛠 Tools Used

* Logisim

## 📚 Key Concepts Learned

* Data path vs control path
* Clocked digital systems
* Memory read/write operations
* Instruction-based CPU design

## 🔮 Future Improvements

* Add branching instructions
* Expand instruction set
* Introduce multiple registers
