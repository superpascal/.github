# SuperPascal

Welcome to the **SuperPascal GitHub organization**.

SuperPascal is an **educational computing stack** that spans **language design, compiler construction, operating systems, and real hardware**. The goal is to let students progress from *writing their first programs* to *understanding an entire computer system* — without black boxes.

This organization hosts the core projects that together form the **SuperPascal ecosystem**.

---

## What is SuperPascal?

SuperPascal is a modern rethinking of Pascal as a **teachable systems language**:

* Strong structure and readability
* Predictable performance
* Minimal hidden behavior
* Designed to scale from education to real systems programming

SuperPascal is not nostalgia-driven. It is intentionally chosen because:

* Pascal-like languages are ideal for teaching correctness and structure
* The language maps cleanly to simple, inspectable hardware
* Students can understand the entire toolchain, end to end

---

## The SuperPascal Stack

The SuperPascal ecosystem is built in **layers**, each reinforcing the others.

```
┌─────────────────────────────┐
│   Applications & Games      │  ← written in SuperPascal
├─────────────────────────────┤
│        PascalOS             │  ← OS layer
├─────────────────────────────┤
│     SuperPascal             │  ← Language and Compiler
├─────────────────────────────┤
│   Hardware & Toolchain      │  ← resistor2compiler
└─────────────────────────────┘
```


---

## Repositories

### 🟦 `superpascal`

**[https://github.com/superpascal/superpascal](https://github.com/superpascal/superpascal)**

The **SuperPascal language and compiler**.

This repository contains:

* The SuperPascal language specification
* The compiler implementation
* Example programs and tests

It is the **entry point** to the ecosystem:

* beginners learn to program here
* advanced students study parsing, typing, code generation, and optimization

SuperPascal is designed to run on both modern machines and constrained educational hardware.

---

### 🟩 `PascalOS`

**[https://github.com/superpascal/PascalOS](https://github.com/superpascal/PascalOS)**

The **operating system layer** for SuperPascal.

PascalOS (also referred to as **SuperPascalOS**) is:

* inspired by OS-9
* written primarily in SuperPascal
* designed for a 65C816-based computer with a transparent CPLD-based MMU

PascalOS demonstrates:

* cooperative multitasking
* per-process memory isolation
* relocatable modules
* device drivers and IPC

It exists to answer the question:

> *What would an operating system look like if it were designed first and foremost to be understood?*

---

### 🟨 `resistor2compiler`

**[https://github.com/superpascal/resistor2compiler](https://github.com/superpascal/resistor2compiler)**

An educational project that connects **physical electronics to software**.

`resistor2compiler` explores:

* how real hardware signals become digital values
* how those values flow into a compiler
* how programs ultimately execute on a CPU

This project helps students understand that:

* computers are not magic
* software abstractions rest on physical reality

It is especially valuable for bridging:

* electronics
* computer architecture
* compiler theory

---

## Educational Vision

SuperPascal is designed to support a **long learning arc**:

* **Ages 13–18:**

  * Learn SuperPascal
  * Build and program a real computer
  * Write games and small applications

* **University level:**

  * Study compilers via `superpascal`
  * Study operating systems via `PascalOS`
  * Study hardware–software boundaries via `resistor2compiler`

All without switching languages or mental models.

---

## Design Principles

Across all repositories, the same principles apply:

* **Clarity over cleverness**
* **Determinism over raw performance**
* **Inspectability over abstraction layers**
* **Education before optimization**

These are not limitations — they are deliberate design choices.

---

## Getting Started

1. Start with **`superpascal`** to learn the language
2. Explore **`PascalOS`** to see systems programming in SuperPascal
3. Dive into **`resistor2compiler`** to understand how software meets hardware

Each repository stands alone, but together they form a complete system.

---

## Status

The SuperPascal ecosystem is actively evolving.

Design documents are treated as first-class artifacts, and repositories may include:

* formal PRDs
* architectural write-ups
* educational notes

---

## Final Note

The SuperPascal organization exists to preserve something rare in modern computing:

> **The ability to understand the whole machine.**

If that idea resonates with you, you’re in the right place.
