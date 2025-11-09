# Assembly Number Guessing Game (MASM 6.11) 🎯

> **Note:** This project was originally created by **Ali Hassan Soomro** (2017).  
> I am sharing it here **for educational and learning purposes only** as part of my study of Assembly Language Programming (COAL - 4th Semester).  
> All original credit goes to the author.

---

## 🧠 Overview
A simple **number guessing game** written in **x86 Assembly (MASM 6.11)** designed to run under **DOSBox**.  
The program demonstrates basic Assembly programming concepts such as:

- User input handling using interrupts (`INT 21h`)  
- Stack operations (`PUSH` / `POP`)  
- Register manipulation and arithmetic  
- Conditional jumps and loops (`JE`, `JC`, `JMP`)  
- Overflow handling  

---

## 📘 Author Information
- **Original Author:** Ali Hassan Soomro  
- **Date:** 24 December 2017  
- **Assembler:** MASM 6.11  
- **Platform:** DOSBox 0.74 / DOS environment  

---

## ⚙️ How to Run

1. **Install MASM 6.11** inside DOSBox  
2. Place the `.ASM` file inside your MASM working directory  
3. Open DOSBox and type:

   ```bash
   mount c c:\masm
   c:
   masm guessing_game.asm;
   link guessing_game.obj;
   guessing_game.exe
