# 🏆 8085 Simulator

The **8085 Simulator** is a C++ program that emulates the functionality of an **Intel 8085 microprocessor**, providing a platform to understand and test **8085 assembly language programs** without the need for physical hardware.

---

## 🚀 Features

✅ **Complete Instruction Set Simulation** - Supports the full 8085 instruction set.

✅ **Memory Management** - Simulates memory read and write operations.

✅ **No Physical Hardware Needed** - Run assembly programs directly on your system.

---

## 📌 How to Use

💡 Enter commands as you would on an **8085 microprocessor**.

💡 Use the `HLT` command to terminate execution.

---

## 🔧 Prerequisites

Before running the simulator, ensure you have:

🔹 **Basic Knowledge of 8085 Microprocessor** (Opcodes, Instructions, etc.)

🔹 **C++ Compiler Installed** (e.g., GCC, Clang, MSVC)

---

## 🛠️ Compilation & Execution

To compile the program, use the following command:

```bash
 g++ 8085Simulator.cpp -o 8085Simulator
```

To run the simulator:

```bash
 ./8085Simulator
```

---

## 📝 Example Usage

```assembly
 MVI A, 0x05   ; Load 5 into register A
 MVI B, 0x03   ; Load 3 into register B
 ADD B         ; Add register B to A
 HLT           ; Stop execution
```

---


⭐ **If you found this project helpful, consider giving it a star!** ⭐

