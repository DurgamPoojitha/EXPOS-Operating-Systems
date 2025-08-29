⚙️ EXPOS – Case Study

Extended Simple Operating System (EXPOS) implementation and case study.
This project explores OS concepts like memory management, scheduling, interrupts, file system design, and multitasking through the XSM Simulator.

👨‍💻 Team Members

Diya Bhat – CB.SC.U4CSE23319

Durgam Poojitha – CB.SC.U4CSE23320

Jai Subiksha T – CB.SC.U4CSE23327

Mahasri M – CB.SC.U4CSE23335

🚀 Project Stages
🔧 Stage 1: Setting up the System

Configure XSM simulator.

Initialize OS, allocate memory, format disk.

Verify using basic commands.

📂 Stage 2: File System

Create/load files using xfs-interface.

Manage free blocks, file metadata, and disk space allocation.

🖥️ Stage 3: Bootstrap Loader

Assembly program to print HELLO_WORLD.

Loads kernel into memory and hands control to OS.

💻 Stage 4: SPL Programming

Learn System Programming Language (SPL).

Example: Printing odd numbers, writing system calls & handlers.

🐞 Stage 5: Debugging

Debug using XSM tools.

Inspect registers, set breakpoints, monitor memory.

👤 Stage 6: Running User Programs

User programs run in user mode via system calls.

Implemented HALT instruction & exception handling.

📜 Stage 7: ABI & XEXE Format

Understand Application Binary Interface rules.

Learn XEXE executable file format (headers, segments, entry point).

⏱️ Stage 8: Timer Interrupt

Implement multitasking with timer interrupts.

Update process states and enable time-sharing.

🗂️ Stage 9: Kernel Stack

Manage function call records, local variables, return addresses.

Prevent stack overflow & handle interrupts.

🖨️ Stage 10: Console Output

Implement OS-level print system calls for output display.

💡 Stage 11: EXPL Language

Learn EXPOS Programming Language (EXPL).

Write high-level programs with memory management & system calls.

🧵 Stage 12: Multiprogramming

Context switching & CPU scheduling.

Run multiple processes concurrently.

🖥️ Stage 13: Boot Module

First program executed during startup.

Loads OS into memory & transfers control to kernel.

🔄 Stage 14: Round Robin Scheduler

Implemented time-slice scheduling.

Fair CPU allocation among processes.

📑 Stage 15: Resource Manager Module

Manage system resources efficiently.

Test program: Print numbers 1–100.

⌨️ Stage 16: Console Input

Handle user input via keyboard.

Pass commands/data to OS functions.

📥 Stage 17: Program Loader

Load executables into memory.

Set up process address space before execution.

💽 Stage 18: Disk Interrupt Handler

Manage disk I/O.

Handle read/write operations on disk.

⚠️ Stage 19: Exception Handling

Handle exceptions: illegal memory access, invalid instructions, divide-by-zero, page faults.

🧪 Stage 20: Process Creation & Synchronization

Implement Fork & Exit system calls.

Manage Process Control Blocks (PCB), address duplication, cleanup.

🛠️ Tools & Technologies

XSM Simulator 🖥️

SPL (System Programming Language)

EXPL (EXPOS Programming Language)

Assembly Programming

Linux Environment

📂 Project Structure
expos-case-study/
│
├── stage1-setup/
├── stage2-filesystem/
├── stage3-bootloader/
├── stage4-spl-programs/
├── stage5-debugging/
├── stage6-user-programs/
├── ...
└── README.md

🎯 Key Learning Outcomes

✅ Understand OS internals: process scheduling, interrupts, exception handling.
✅ Gain hands-on experience with system programming languages (SPL & EXPL).
✅ Learn to implement bootloaders, loaders, schedulers, and file systems.
✅ Strengthen debugging & low-level programming skills.

👩‍💻 Contributors
Name	Roll No.
Diya Bhat	CB.SC.U4CSE23319
Durgam Poojitha	CB.SC.U4CSE23320
Jai Subiksha T	CB.SC.U4CSE23327
Mahasri M	CB.SC.U4CSE23335
📜 License

This project is for academic learning purposes only.

✨ Built with curiosity and low-level programming to understand the core of Operating Systems.
