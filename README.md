# 📖 get_next_line — Reading a Line from a File Descriptor

## 🧭 Project Description

**get_next_line** is a 42 School project whose goal is to implement a function capable of reading **one line at a time** from a file descriptor.

The function must handle:

- Reading from files and standard input
- Buffer management across multiple calls
- Dynamic memory allocation
- Persistent state between function calls
- Efficient string manipulation without memory leaks

This project builds a deep understanding of how low-level I/O works in C using `read`, and how to manage memory and buffers correctly.

---

## 🎯 Learning Objectives

With get_next_line, you learn to:

- Use the `read` system call properly
- Manage static memory across function calls
- Handle partial reads and buffer concatenation
- Extract lines safely and efficiently
- Prevent memory leaks in complex flows
- Understand file descriptor behavior
