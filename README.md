# XV6 Operating System Enhancements

A comprehensive suite of kernel-level modifications and feature implementations for the MIT xv6 operating system, developed as part of advanced OS laboratory coursework.

## 📌 Overview
This repository contains the C and Assembly source codes for five major operating system modules, extending the base xv6 kernel with modern OS capabilities including advanced scheduling, synchronization, and virtual memory management.

## 🚀 Key Implementations
* **Lab 1: Kernel Boot & Console:** Customization of the bootloader sequence, console output enhancements, and GDB tracing setup.
* **Lab 2: System Calls:** Implementation of custom kernel-space utilities (`grep`, `make_duplicate`) and process priority setters.
* **Lab 3: CPU Scheduling:** Development of a heterogeneous E/P-core scheduling algorithm with dynamic load balancing and throughput tracking.
* **Lab 4: Synchronization:** Implementation of robust locking mechanisms (Spinlocks, Sleeplocks, Ticket locks) and mitigation of race conditions.
* **Lab 5: Virtual Memory:** Design of page replacement algorithms (FIFO, LRU, LFU, Clock) to handle page faults and memory swapping efficiently.

## 🛠️ Tech Stack
* **Languages:** C, x86 Assembly
* **Tools:** QEMU Emulator, GCC, GDB, Makefile
