# 📘 L-01: Basics of Programming and Java

---

## 🧠 What is a Program?

A **program** is a set of instructions given to a computer to perform a specific task.

> 🧾 **Analogy**:
> Just like you give step-by-step instructions to a cook to make *Maggi*, you give instructions to a computer using a program.

---

## 💻 What is Programming?

**Programming** is the process of writing instructions that a computer can follow to complete a task.

### 🔁 Analogy:

| Role         | Real World   | Programming |
| ------------ | ------------ | ----------- |
| You          | Person       | Programmer  |
| Cook         | Executes     | Computer    |
| Recipe Steps | Instructions | Program     |

---

## 👩‍💻 Who is a Programmer?

A **programmer** is a person who:

* Writes code to instruct computers.
* Solves problems using logic and programming languages.

---

## 📊 What is Data and Information?

* **Data**: Raw facts and figures (e.g., `25`, `John`, `102°C`)
* **Information**: Processed, meaningful data (e.g., *Average temperature of Patna is 32°C*)

---

## 🧮 What is an Algorithm?

An **algorithm** is a step-by-step method to solve a specific problem.

> 💡 Like a cooking recipe:
> `Step 1 → Step 2 → Step 3 → Result`

---

## 🧱 What is DSA (Data Structures & Algorithms)? Why is it important?

* **Data Structures**: Organize data (e.g., Arrays, Linked Lists, Stacks)
* **Algorithms**: Logic to process and manipulate that data

### 🧰 Analogy:

DSA is like the **foundation and blueprint** of a building (your program).
🧱 Strong DSA = Strong programming base

> ✅ DSA is crucial for coding interviews (Google, Amazon, etc.)

---

## 🚀 Applications of Programming

* 🌐 Web & Mobile Development (e.g., YouTube, Swiggy)
* 🤖 Automation (bots, scripts)
* 🎮 Game Development
* 📊 Data Science & AI
* 🔒 Cybersecurity
* ⚙️ Embedded Systems
* 💼 Earning Opportunities: Freelancing, Jobs, Startups

---

## 👨‍🏫 Programming Paradigms

Paradigms define different ways to write and structure your code
---

### 1. 🔧 Procedural Programming

* Code is written as a sequence of instructions
* Focus: **Functions/Procedures**
* 🧪 **Languages**: C, Pascal

#### 📌 Example in C:

```c
#include <stdio.h>

void greet() {
    printf("Hello from Procedural Programming!\n");
}

int main() {
    greet();
    return 0;
}
```

---

### 2. 🔁 Functional Programming

* Based on **pure functions** with no side effects.
* Focus: **What to solve**, not how.
* ⚙️ **Languages**: JavaScript, Haskell

#### 📌 Example in JavaScript:

```javascript
// Pure Function
function add(a, b) {
    return a + b;
}

console.log(add(3, 4)); // Output: 7
```
#### 🔁 What is a Function?

A **function** is a reusable block of code that performs a specific task when called.


> ✅ **Pure Function**:

* Always returns same output for same input.
* No side effects (doesn't modify external variables).

---

### 3. 🧱 Object-Oriented Programming (OOP)

* Based on **objects** that contain data + behavior (methods).
* Focus: **Encapsulation, Inheritance, Modularity**
* 🧑‍💻 **Languages**: Java, Python, C++

#### 📌 Example in Java:

```java
class Animal {
    void sound() {
        System.out.println("Animal makes a sound");
    }
}

public class Main {
    public static void main(String[] args) {
        Animal dog = new Animal();
        dog.sound();
    }
}
```

---

## ☕ Features of Java

* ✔️ Platform Independent (WORA: Write Once, Run Anywhere)
* ✔️ Object-Oriented
* ✔️ Robust and Secure
* ✔️ High Performance (Just-In-Time Compiler)
* ✔️ Multithreaded
* ✔️ Rich APIs and huge community support

---

## 🔄 High-Level vs Low-Level Languages

| Feature             | Low-Level Language     | High-Level Language          |
| ------------------- | ---------------------- | ---------------------------- |
| Example             | Assembly, Machine Code | Java, Python                 |
| Readability         | ❌ Hard to read/write   | ✅ Easy to read/write         |
| Translator Required | ❌ No                   | ✅ Yes (Compiler/Interpreter) |

> 🔁 Compiler/Interpreter converts high-level code into machine code.

---

## 🏛️ Architecture of Java

### 📦 Components

1. **Source Code (`.java`)**:
   Your written program in Java syntax

2. **Compiler (`javac`)**:
   Translates `.java` → `.class` (Bytecode)

3. **JVM (Java Virtual Machine)**:

   * Reads `.class` files
   * Interprets bytecode → Machine code
   * Executes on your CPU

### 🔁 Flow Diagram

```
Source Code (.java)
        ↓
     Compiler (javac)
        ↓
  Bytecode (.class)
        ↓
        JVM
        ↓
  Machine Code (Executed by CPU)
```

---

## 🔧 JVM vs JDK vs JRE

| Component | Full Form                | Purpose                                                   |
| --------- | ------------------------ | --------------------------------------------------------- |
| **JVM**   | Java Virtual Machine     | Runs Java bytecode (.class) on any platform               |
| **JRE**   | Java Runtime Environment | JVM + libraries needed to run Java programs               |
| **JDK**   | Java Development Kit     | JRE + compiler (`javac`) + tools to **develop** Java apps |

---

> ✅ You **write code** in `.java` → **compile** to `.class` using JDK → **run** using JVM (inside JRE)

