# Pixle Programming Language

![Pixle Output](output.png)

> **Pixle** is a custom Domain-Specific Language (DSL) implemented in **Java**, designed for generating graphics, pixel art, and code-based visualizations through a clean and structured syntax.

---

## Table of Contents
- [About](#about)
- [Features](#features)
- [Prerequisites and Installation](#prerequisites-and-installation)
- [How to Run](#how-to-run)
- [Pixle Code Example](#pixle-code-example)
- [Visual Output](#visual-output)
- [Java Interpreter Architecture](#java-interpreter-architecture)
- [License](#license)

---

## About

Pixle was created to provide a simple and accessible interface for programmatically generating images. The language engine, including the Lexer, Parser, and Interpreter, was built from scratch using Java.

The interpreter reads source files with the `.pixle` extension, evaluates the instructions, and exports the final visual result (such as `output.png`).

---

## Features

- **Java-Based**: Runs on the JVM for reliable cross-platform execution.
- **Built-in Graphics API**: Simple primitives for drawing pixels, shapes, color manipulation, and canvas setup.
- **Variables and Control Flow**: Supports variable declarations, loops (`for`/`while`), and conditional logic (`if`).
- **Automated Export**: Direct rendering to image formats (PNG / JPEG).

---

## Prerequisites and Installation

### Requirements
* **Java Development Kit (JDK)** version 17 or higher.
* **Git** (for cloning the repository).

### Installation
```bash
git clone [https://github.com/your-username/pixle.git](https://github.com/your-username/pixle.git)
cd pixle
