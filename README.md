# SyntaX (for JavaScript) 🚀

**SyntaX** is a lightweight, easy-to-use utility library designed to bring the **simplicity of Python's syntax** to the **Node.js Ecosystem**.

Are you tired of JavaScript's asynchronous `readline` complexity or verbose `console.log` boilerplate? **SyntaX** allows you to write cleaner, more readable code. It provides a synchronous, straightforward way to handle CLI tasks without the callback hell.

---

## 🌟 Key Features

* **Python-like Syntax:** Familiar functions like `print()`, `input()`, and `randint()`.
* **Synchronous I/O:** Provides a clean, sequential flow for CLI applications.
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
2. Ensure you have `readline-sync` installed in your project.
3. Place `bettersyntax.js` in your project folder.
4. Import the required functions into your script using the standard `require` method.

---

## 🚀 Advanced Installation (System-wide)

If you want to use **SyntaX** globally:

1. Create a global folder for your utilities.
2. Link the file using `npm link` or add the folder to your `NODE_PATH`.
3. Now you can import it from any local project!

---

## 💻 Technical Details

The library wraps Node's internal processes into a synchronous object. By utilizing the spread operator, the `print()` function can handle multiple data types simultaneously, mirroring the flexibility found in the other versions of the SyntaX ecosystem.

---

## Development Comparison

| Feature | Standard Node.js (Vanilla) | **SyntaX for JS** (`bettersyntax`) |
| :--- | :--- | :--- |
| **Output** | `console.log(x + " " + y);` | `print(x, y);` |
| **User Input** | *(Complex Readline Interface)* | `let s = input("Name: ");` |
| **Random Number** | `Math.floor(Math.random() * max);` | `randint(min, max);` |
| **Sleep/Wait** | `setTimeout(() => { ... }, 1000);` | `sleep(1.0);` |
| **Math (Sqrt)** | `Math.sqrt(val);` | `square_root(val);` |
| **Clear Screen** | `console.clear();` | `clear();` |

---

### 👨‍💻 Programmer
**hypernova-developer**
