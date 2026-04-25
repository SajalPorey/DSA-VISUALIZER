# DSA Visualizer

An interactive **Data Structures Visualizer** (dsa visuliser) built with pure **HTML, CSS, and JavaScript**.  
It lets you visualize **Linked Lists, Stacks, and Queues** with smooth animations, neon UI, and interactive operations.

> App title: **DSA VISUALIZER PRO**

---

## 🚀 Features

- 🔗 **Linked List Visualizer**
  - Singly Linked List  
  - Doubly Linked List  
  - Circular Linked List (arranged in a circle)  
  - Insert, delete, and search nodes  
  - Found node glows **hot pink** with animation  

- 📚 **Stack Visualizer**
  - Push, Pop, Clear  
  - Vertical stack with **TOP** tag  

- 🚌 **Queue Visualizer**
  - Linear Queue & Circular Queue  
  - Enqueue, Dequeue, Clear  
  - **FRONT** and **REAR** tags  

- 🧮 **Dynamic Programming Visualizer**
  - **Longest Common Subsequence (LCS)**
    - Interactive DP table visualization
    - Trace the optimal path with highlighted cells
    - Shows LCS string, length, and table dimensions
  - **Fractional Knapsack**
    - Greedy algorithm optimization
    - Real-time calculation of maximum profit
    - Item cards show value, weight, ratio, and decisions
    - Visual representation of items taken (full/partial/skipped)

- 🎨 **Modern UI**
  - Neon gradient theme  
  - Glassmorphism-style cards  
  - Smooth transitions and glowing effects
  - Interactive stat cards with real-time calculations  

---

## 🧱 Tech Stack

- **HTML5**
- **CSS3**
- **Vanilla JavaScript**

---

## 📂 Project Structure

```text
.
└── index.html   # Contains HTML, CSS, and JS for the visualizer
```
▶️ How to Run

Download or clone the project.

Open index.html in any modern browser (Chrome, Edge, etc.).

No server or build step needed – it’s fully client-side.

🕹️ How to Use

Choose Data Structure from the dropdown:

-Linked List

-Stack

-Queue

-Dynamic Programming

**Linked List**

-Select type: Singly / Doubly / Circular

-Insert Node – add a value

-Delete Node – remove by value

-Search Node – highlights matching node in hot pink

Clear Highlight – removes glow effect

**Stack**

-Push – add element

-Pop – remove top element

-Clear – empty the stack

**Queue**

-Select: Linear Queue or Circular Queue

-Enqueue – add element at rear

-Dequeue – remove element from front

-Clear – empty the queue

**Dynamic Programming**

-**Longest Common Subsequence (LCS)**
  - Enter two strings
  - Click "Build DP Table" to visualize the computation
  - View the DP matrix with trace highlighting
  - See the resulting LCS string and its length

-**Fractional Knapsack**
  - Set the knapsack capacity
  - Enter items in `value,weight` format (one per line)
  - Click "Solve Knapsack" to compute the optimal solution
  - View profit cards showing which items are taken (full/partial/skipped)

💡 Future Improvements

Add arrays, trees, and graphs visualizations

Step-by-step traversal animations

Show algorithm explanation and time complexity
