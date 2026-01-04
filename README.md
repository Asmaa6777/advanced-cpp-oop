# Modern C++ OOP — CS213 Guide

This repository is a **clear, example-driven guide to Object-Oriented Programming (OOP) and Advanced C++**, based on the **CS213 Object-Oriented Programming course**.
---

## What This Repository Covers

We start by shifting from **structured programming** (a sequence of instructions) to **object-oriented thinking**, where programs are built from objects that combine **data and behavior**, much like real entities in the real world.

From there, the material gradually moves into advanced C++ territory.

### Core OOP Concepts
- **Abstraction** – focusing on *what* an object does, not *how* it does it.
- **Encapsulation** – keeping an object’s internal state safe from outside chaos.
- **Inheritance** – building new classes from existing ones.
- **Polymorphism** – one interface, many behaviors (and fewer `if` statements).

These ideas are demonstrated using:
- Virtual functions and dynamic binding  
- Abstract classes and interfaces  
- Friend functions (used carefully, not recklessly)

---

### Generic Programming
- Function and class **templates**
- Writing reusable, type-safe, and efficient code without duplication

---

### Standard Template Library (STL)
- Containers: `vector`, `list`, `deque`, and friends  
- Iterators and algorithms (`sort`, `find`, `count`, …)  
- How STL helps you write less code and fewer bugs at the same time

---

### Problem-Solving Techniques
- **Recursion** – solving problems by solving smaller versions of themselves  
- **Backtracking** – trying possibilities, undoing mistakes, and trying again (politely)

---

### Memory & Resource Management
- Dynamic memory allocation  
- Raw pointers vs **smart pointers** (`unique_ptr`, `shared_ptr`)  
- **RAII**: acquiring resources safely and releasing them automatically  
- How to avoid memory leaks without crying

---

### Modern C++ Features
- Features from **C++11 to C++20**
- `auto`, lambda expressions, ranges  
- Safer, cleaner alternatives to old-style C++  
- An introduction to **modules** instead of endless header files

---

### Safety and Robustness
- **Const correctness** to prevent accidental modification  
- **Exception handling** for predictable failure instead of undefined chaos  

---

## OOP Models (Quick Comparison)

This repo also briefly explores different object-oriented styles:
- **Pure OOP (Smalltalk)** – everything is an object  
- **Class-based OOP (C++ / Java)** – objects are instances of classes  
- **Prototype-based OOP (JavaScript)** – objects inherit directly from objects  

This helps clarify that OOP is a concept, not a single implementation.

---

## How to Use This Repository

- Read the explanations before the code  
- Run the examples, break them, and fix them  
- Focus on *why* a design works, not just *how* to write it  

If a concept feels confusing, there’s probably an analogy nearby waiting to save you.

---

## Final Note

Think of programming paradigms like building a house:

- **Structured programming** is a long checklist of steps  
- **Object-Oriented Programming** is assembling pre-built components, each managing its own internal details  

This repository is about learning how to design those components **cleanly, safely, and intelligently**—using modern C++ as the tool of choice.

Happy coding.
