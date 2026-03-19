# Variable Scope & Memory Visualizer

This interactive educational tool is designed to help students understand one of the most fundamental concepts in programming: **Variable Scope** (Global vs. Local variables) and how memory is managed during function calls.

<img width="1722" height="965" alt="image" src="https://github.com/user-attachments/assets/2f3d3e99-c9c0-4ab3-8c5d-a150a07fac90" />

## 🎯 What will you learn?
By using this tool, you will visually understand:
1. **Global Scope (Heap / Data Segment):** Variables created outside functions that live for the entire duration of the program.
2. **Local Scope (Stack):** Variables created inside functions that are temporary. They are created when a function starts and completely destroyed when the function ends.
3. **Why Errors Happen:** Why trying to use a local variable outside of its function causes a `NameError` (Python) or `Compilation Error` (C++).

## 🚀 How to use this app for learning

1. **Choose your Language:** At the top right of the Code Execution panel, select either **Python** or **C++**. The concepts are similar, but the syntax is different.
2. **Step-by-Step Execution:** 
   - Click the **"Next"** button to execute the code line by line.
   - Watch the yellow highlight move through the code.
   - Read the explanation box below the code to understand exactly what is happening at that moment.
3. **Watch the Memory (Right Panel):**
   - See how the `global_var` is placed in the large outer box (Global Scope).
   - See how a temporary inner box (Local Scope) appears when the `explore()` function is called.
   - Watch the `local_var` appear inside that inner box.
   - **Crucial Step:** Notice how the inner box bursts into flames and disappears when the function finishes! This visually represents memory being freed.
4. **Check the Terminal:** The terminal output shows what the program actually prints. Notice the highlight effect showing the most recent output.
5. **Go Back or Reset:** If you missed something, click **"Prev"** to go back one step, or **"Reset"** to start over.
6. **Read the Theory:** Scroll down to the "Theory & Concept" section for clear definitions and real-world examples of when to use Global vs. Local variables.

## 🌍 Language Support
Click the **"中 / EN"** button at the top right to switch between English and Traditional Chinese explanations at any time.
