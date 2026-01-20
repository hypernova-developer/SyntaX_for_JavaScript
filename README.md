# SyntaX (for JavaScript) 🚀

**SyntaX** is a lightweight, easy-to-use utility library designed to bring the **simplicity of Python's syntax** to the **Node.js Ecosystem**.

Are you tired of JavaScript's asynchronous `readline` complexity or verbose `console.log` boilerplate? **SyntaX** allows you to write cleaner, more readable code. It provides a synchronous, straightforward way to handle CLI tasks without the callback hell.

---

## 🌟 Key Features

* **Python-like Syntax:** Familiar functions like `print()`, `input()`, and `randint()`.
* **Synchronous I/O:** Uses `readline-sync` logic to provide a clean, sequential flow.
* **Zero Complex Dependencies:** Lightweight and optimized for Node.js environments.
* **Flexible Output:** `print()` supports multiple arguments of any type.
* **Human-Readable Math:** Simplified random and square root functions.

---

## 🛠️ Usage & Examples

To keep this documentation clean, we have provided a dedicated example file. You can find comprehensive usage examples covering:

* **Simplified I/O** (print and input with optional prompts)
* **Logic & Math Helpers** (randint, square_root)
* **System Utilities** (clear screen and sleep)

👉 **Check out [samples.js](./samples.js) for ready-to-use code snippets!**

---

## 📂 Installation

1. Download the **bettersyntax.js** file.
2. Ensure you have `readline-sync` installed: `npm install readline-sync`.
3. Place `bettersyntax.js` in your project folder.
4. Import it using:
   ```javascript
   const { print, input, randint, sleep, clear } = require('./bettersyntax');
