# 🎭 Conversion of Regular Expression to NFA with Visualization  

## 📌 Introduction  
This project provides a **comprehensive solution** for converting **regular expressions** into **Non-deterministic Finite Automata (NFA)** using **Java**. It also includes tools for **visualizing** the resulting automaton, making it a valuable **educational resource** for understanding **automata theory, formal languages, and pattern recognition**.  

The project consists of **three main components**:  

1. **PostfixToNFA Class** – Converts a regular expression from **infix notation** to **postfix notation** and constructs the **NFA** using **Thompson's construction**.  
2. **Visualise Class** – Generates a **visual representation** of the NFA using **Graphviz**.  
3. **Python Script for Visualization** – Renders the NFA graph from a **Graphviz dot file** into a graphical format for easy analysis.  

---

## 🔹 Components  

### **1️⃣ PostfixToNFA Class**  
The **PostfixToNFA** class handles the **conversion of a regular expression into an NFA** using the following operations:  

- **Concatenation (`.`)** – Connects NFAs sequentially.  
- **Union (`|`)** – Creates branching paths in the NFA.  
- **Kleene Star (`*`)** – Allows loops within the NFA.  

The class converts the **infix expression** to **postfix notation** and then applies **Thompson's construction** to create the **NFA**, with each operation represented by **specific state transitions** in the automaton.  

---

### **2️⃣ Visualise Class**  
The **Visualise** class produces a **Graphviz dot file** from the **NFA structure**, displaying:  

✅ **Start and Accept States** – Defines where the **NFA starts and ends**.  
✅ **Transitions** – Illustrates **state changes** and **epsilon transitions** (non-consuming moves).  
✅ **Graph Attributes** – Configures the **graph layout** for **better readability**.  

---

### **3️⃣ Python Script for Visualization**  
A **Python script** reads the **generated dot file** and renders it as an **image (.png) or PDF**, enabling users to visually examine the **NFA's structure and transitions**.  

---

## 🚀 **Usage**  

### **1️⃣ Convert the Regular Expression**  
Use the **PostfixToNFA** class to **transform** the **regular expression** into an **NFA**.  

### **2️⃣ Visualize the NFA**  
- The **Visualise class** generates a **Graphviz dot file**.  
- The **Python script** reads the **dot file** and **creates a visual representation** for easy analysis.  

---

## 🎨 **Output**  
The project generates:  

📄 **A `.dot` file** describing the **NFA's structure**.  
🖼️ **A graphical visualization** in **`.png` or `.pdf` format** for easy examination of the automaton.  

---

## 🛠️ **Technologies Used**  
- **Java** – Core programming for **NFA conversion**  
- **Graphviz** – Used for **NFA visualization**  
- **Python** – Renders **Graphviz dot files** into images  
- **Thompson's Construction Algorithm** – Used for **NFA generation**  

---


