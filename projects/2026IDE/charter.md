# 2026 IDE — Project Charter

**Project:** 2026 IDE — Structured Programming Environment  
**Founding date:** 16 September 2026  
**Purpose:** To bring disciplined, human-readable structured programming into the modern software-development environment.

---

## 1. The Purpose

The 2026 IDE is intended to provide a modern programming environment in which **program structure, human understanding and long-term maintainability are primary design considerations**.

It will combine the disciplined structured-programming methodology of the early 1980s with contemporary graphical interfaces, multiple programming languages, automated testing, modern compilers and artificial intelligence.

The objective is not to return to an earlier technological era.

**The objective is to take forward what was valuable in that era and combine it with what is now possible.**

---

## 2. The Challenge

Modern software development has accumulated many languages, frameworks, libraries, programming paradigms, development environments and practices.

This has produced enormous capability, but it has also produced fragmentation.

Program structure may become distributed across:

- source files;
- classes and objects;
- event handlers;
- forms;
- callbacks;
- framework mechanisms;
- generated code;
- libraries;
- configuration;
- and implementation-specific conventions.

Consequently, the meaning and architecture of a program can become difficult for another human being to understand, modify, test and maintain.

The 2026 IDE seeks to address this by **placing the human-readable structure of the program above its implementation language**.

---

## 3. The Foundational Principle

> **The program shall be designed as a comprehensible structure before it is implemented as source code.**

The programmer should be able to understand the program from its highest-level description and progressively descend into its constituent procedures, functions and modules.

A well-designed program should be capable of being **read as naturally as a well-written book**.

---

## 4. One Program — Multiple Representations

The system shall maintain a common underlying representation from which multiple representations of the same program can be produced.

At minimum:

### Representation I — English Design

A clear English-language description of what the program is intended to accomplish.

### Representation II — Nassi–Shneiderman Design

A graphical representation of the program's structure and control flow.

### Representation III — Structured Pseudocode

English-language structured pseudocode representing the logic expressed by the Nassi–Shneiderman design.

### Representation IV — Production Source

Modular, structured and fully commented source code generated for the selected implementation language.

These are **not four unrelated documents**.

They are four views of the same program.

> **Like editions of the same book, each suitable for a different purpose.**

---

## 5. No Black Box

The 2026 IDE shall not require an organisation to surrender understanding or ownership of its software to an opaque development system.

A completed software production should expose:

- its purpose;
- its design;
- its structure;
- its pseudocode;
- its source code;
- its modules;
- its tests;
- and its documentation.

The resulting software should remain understandable and usable **outside the IDE that produced it**.

---

## 6. Language Independence

The structural representation shall not be intrinsically dependent upon any particular implementation language.

The same program design should, where technically appropriate, be capable of being translated into different target languages.

For example:

    Structured Program
           │
           ├──► Python
           ├──► Rust
           ├──► C
           ├──► C++
           └──► future languages

The implementation language therefore becomes a **target**, rather than the fundamental definition of the program.

---

## 7. Structured Programming

The system shall favour explicit, comprehensible control structures including:

- sequence;
- selection;
- iteration;
- procedures;
- functions;
- modular decomposition;
- defined interfaces;
- controlled termination;
- and explicit data flow.

The system shall seek to minimise unnecessary fragmentation of control flow.

The objective is not to reject every programming technique developed since structured programming emerged.

The objective is to ensure that **the overall structure remains visible, comprehensible and controllable by the programmer**.

---

## 8. Artificial Intelligence

AI shall be used primarily to **assist the programmer in implementing and maintaining the design**, rather than replacing the design itself with an opaque generated artefact.

The AI should be able to work from the structured representation and assist with:

- code generation;
- translation between target languages;
- documentation;
- test generation;
- error analysis;
- refactoring;
- optimisation;
- and maintenance.

The human-readable design remains authoritative.

---

## 9. Verification and Testing

The system shall incorporate the principle that successful compilation is **not equivalent to successful software**.

The development cycle shall therefore include:

    DESIGN
      ↓
    IMPLEMENT
      ↓
    COMPILE
      ↓
    EXECUTE
      ↓
    TEST
      ↓
    CRITICAL PATH TESTING
      ↓
    TEST AFFECTED PATHS
      ↓
    VERIFY
      ↓
    RELEASE

Compiler errors, test failures and other feedback should be capable of returning to the development representation so that corrections occur at the appropriate structural level.

---

## 10. Interoperability

The system's broader purpose is to help overcome fragmentation within software development.

A common structural representation can provide a shared conceptual foundation across:

- programmers;
- teams;
- organisations;
- programming languages;
- development environments;
- AI systems;
- and generations of technology.

The objective is **interoperability without requiring uniformity of implementation**.

---

## 11. Longevity

The system shall treat software as something that should survive its original implementation environment.

A program designed in 2026 should retain its essential structure and meaning even if:

- its programming language becomes obsolete;
- its compiler disappears;
- its IDE is abandoned;
- its framework is superseded;
- or its original development organisation no longer exists.

The enduring asset should be the **program itself**, not merely the particular implementation used at one point in history.

---

## 12. Human Benefit

The ultimate purpose of the project is **human benefit**.

The system should seek to make sophisticated software development:

- more understandable;
- more maintainable;
- more collaborative;
- more accessible;
- more efficient;
- more creative;
- and more durable.

It should enable humans to spend more of their effort **thinking about issues and designing resolutions**, while allowing machines and AI to undertake increasing amounts of mechanical implementation work.

---

# Founding Statement

> **The 2026 IDE is an attempt to bring together the discipline of structured programming with the capabilities of modern computing and artificial intelligence.**
>
> **It does not seek to turn the clock backwards. It seeks to recover a valuable property of software development — that a program can be understood by reading its structure — and carry that property forward into the future.**
>
> **The program shall remain comprehensible to the human who designed it, the programmer who maintains it, the organisation that owns it, and the generations of technology that may implement it in the future.**
