# 🧠 CSP Visualizer – AI Constraint Satisfaction Simulator

> 🚀 An interactive AI-powered web application that visually demonstrates how **Constraint Satisfaction Problems (CSPs)** are solved using **Backtracking Algorithms**.

---

## 📌 Project Overview

CSP Visualizer is designed to bridge the gap between **theory and visualization** in Artificial Intelligence.

Instead of simply computing solutions, this tool **animates the entire decision-making process of AI**, allowing users to observe:

* How variables are selected
* How values are assigned
* How constraints are checked
* How conflicts are detected
* How backtracking occurs

---

## 🎯 Objectives

* Visualize **Constraint Satisfaction Problems (CSPs)** in real time
* Demonstrate **Backtracking Algorithm step-by-step**
* Help students understand **AI problem-solving intuitively**
* Create a **professional, interactive learning tool**

---

## 🧩 Problems Implemented

### 🌍 1. Map Coloring Problem (Australia)

**Description:**
Assign colors to regions such that no two adjacent regions share the same color.

**Components:**

* **Variables:** WA, NT, SA, Q, NSW, V, T
* **Domain:** {Red, Green, Blue}
* **Constraints:** Adjacent regions must have different colors

**Key Features:**

* Dynamic region coloring
* Adjacency-based constraint checking
* Step-by-step assignment
* Visual backtracking with conflict highlighting

---

### ♛ 2. N-Queens Problem

**Description:**
Place N queens on an N×N chessboard such that no two queens attack each other.

**Constraints:**

* No same row
* No same column
* No same diagonal

**Key Features:**

* Interactive chessboard
* Adjustable board size (4–8)
* Animated queen placement
* Real-time conflict detection
* Backtracking visualization

---

## 🎨 UI/UX Highlights

* 🌙 Modern **dark theme**
* 🧊 Glassmorphism-inspired UI
* ⚡ Smooth animations and transitions
* 🧠 “AI Thinking” simulation effect
* 📱 Fully responsive design

---

## ⚙️ Interactive Controls

* 🔀 Switch between problems
* 🎚️ Animation speed control
* ▶️ Start solving
* 🔁 Reset simulation
* 📏 Board size slider (N-Queens)

---

## 🧠 Core Concepts Demonstrated

### ✔ Constraint Satisfaction Problem (CSP)

A problem defined by:

* Variables
* Domains
* Constraints

---

### ✔ Backtracking Algorithm

A recursive algorithm that:

1. Selects a variable
2. Assigns a value
3. Checks constraints
4. Proceeds if valid
5. Otherwise, **backtracks and tries another value**

---

### ✔ Constraint Checking

* **Map Coloring:** Adjacency validation
* **N-Queens:** Row, column, diagonal checks

---

### ✔ State Space Tree

* Nodes → Partial solutions
* Edges → Assignments
* Leaves → Valid or failed solutions

---

## 🔍 How It Works

1. **Variable Selection**
   AI selects the next variable to assign

2. **Value Assignment**
   Tries values from the domain

3. **Constraint Checking**
   Ensures no rules are violated

4. **Conflict Detection**
   Identifies invalid states

5. **Backtracking**
   Reverts previous decisions

6. **Solution Found**
   All constraints satisfied

---

## 🛠️ Tech Stack

* **Frontend:** HTML5, CSS3, JavaScript (ES6)
* **UI Design:** Glassmorphism, CSS Animations
* **Logic:** Recursive Backtracking Algorithm
* **Rendering:** DOM Manipulation

---

## ✨ Special Features

* 🔥 Step-by-step AI visualization
* 💡 Conflict highlighting
* 🎞️ Smooth animation delays
* 📊 Educational clarity over raw output
* 🎯 Presentation-ready design

---

## 🎓 Learning Outcomes

This project helps in understanding:

* Artificial Intelligence problem solving
* Backtracking and recursion
* Constraint propagation
* Algorithm visualization
* Interactive UI design

---

## 🚀 Future Enhancements

* Add **MRV (Minimum Remaining Values) heuristic**
* Implement **Forward Checking**
* Add **Sudoku CSP Solver**
* Show **step counter & performance metrics**
* Export solution steps

---

## 📸 Demo

> Experience how AI “thinks” while solving problems in real time.

---

## ⭐ Conclusion

CSP Visualizer transforms complex AI concepts into an **intuitive, interactive experience**, making learning engaging and effective.

---

### 🌟 *“Watch AI Think. Understand Every Step.”*
