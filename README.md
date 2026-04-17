# Variable Scope & Memory Visualizer

This interactive educational tool is designed to help students understand one of the most fundamental concepts in programming: **Variable Scope** (Global vs. Local variables) and how memory is managed during function calls.

<img width="1428" height="989" alt="image" src="https://github.com/user-attachments/assets/2c49ab76-d05c-4633-89eb-e5120210025f" />

## 🎯 What will you learn?
By using this tool, you will visually understand:
1. **Global Scope (Heap / Data Segment):** Variables created outside functions that live for the entire duration of the program.
2. **Local Scope (Stack):** Variables created inside functions that are temporary. They are created when a function starts and completely destroyed when the function ends.
3. **Why Errors Happen:** Why trying to use a local variable outside of its function causes a `NameError` (Python) or `Compilation Error` (C++).

## How to Use This App
1. **Study the Concepts:** Begin by reading the "Learning Objective" and "Concept Explanation" sections to grasp the fundamental theory.
2. **Interactive Visualizer:** - Choose your preferred programming language (Python or C++).
   - Use the "Next" button to step through the code line by line.
   - Observe the "Terminal Output" and the "Memory Visualizer" panels to see how Global and Local variables behave in the Heap/Data Segment and Stack.
3. **Clarify Doubts:** Read the "Common Misconceptions" and "Key Takeaways" to avoid typical exam traps.
4. **Think Critically:** Try to answer the "Think & Link" question before revealing the answer.
5. **Self-Assessment:** Complete the interactive quiz at the bottom to test your knowledge. Your score is saved temporarily in your session.

## Learning Advice
Pay close attention to what happens when a function finishes execution. The destruction of local memory (Stack) is a frequent topic in programming questions. 
