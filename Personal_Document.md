# Personal Contribution Document

> 🧑 Author: B13902071 LeOuO/ Pishiou 張存億  
> 🧠 Project: DFS/BFS Graph Visualizer – Group 26 (NTU DSA 2025)  
> 📄 Document Purpose: To clarify my personal contributions in a team project

---

## ✅ My Individual Work: BFS Implementation

I was fully responsible for implementing **Breadth-First Search (BFS)** logic and its interactive visualization. This includes:

### 🔄 BFS Algorithm Logic
- Implemented BFS traversal logic in `script.js` using a queue-based approach.
- Designed step-by-step execution via `generateAllBFSSteps()` and `animateBFS()`.

### 🟧 BFS Node and Edge Animation
- Created BFS state transitions: `unvisited → visiting → visited` using color codes.
- Highlighted BFS edges with animation using `setVisited(true)`.

### 📦 Queue Visualization
- Created and updated the live queue display in the DOM (`#queue-container`).
- Implemented `updateQueueVisualization()` to reflect current BFS queue.

### 🎛️ Step Mode & Button State
- Designed the logic allowing BFS to be executed step-by-step or all at once.
- Handled `run-bfs`, `step-bfs`, and `stop` button logic, preventing conflicting DFS execution.

---

## 🤝 Collaborative Work (With Teammate)

### ✏️ Shared Design and UI/UX
- Co-designed the dark-themed, responsive UI in `style.css`.
- Collaborated on layout elements: sidebar, header, legend, and queue section.

### 🧱 Canvas Setup and Node/Edge Interaction
- Jointly implemented:
  - Canvas resizing and responsiveness (`resizeCanvas`)
  - Node creation (`addNode`) and validation (non-overlapping)
  - Edge creation with directionality and self-loop prevention
  - Node/Edge removal logic (`removeElement`)

### 🖼️ Visual Elements and Legend
- Designed visual distinction:
  - Green: Unvisited
  - Orange: Processing
  - Blue: Visited
  - Red: Visited Edge
- Helped configure the real-time stack/queue title (`#queue-title`) rendering logic.

### 🧪 Debug and Integration
- Tested the full canvas functionality and transitions.
- Ensured consistent interaction across DFS/BFS modes and synchronized button states.

### 📄 Documentation & Presentation
- Participated in writing instructions (`index.html`, `dfs.html`) for user guidance.
- Collaborated on final README and project demonstration setup.

---

## 🏁 Summary

I focused on implementing a robust BFS visualization system while collaborating on all shared UI, input handling, and logic—excluding DFS.  
This collaboration allowed us to develop a fully interactive and educational tool for graph traversal demonstration.

---

📌 **Note:**  
This document was co-produced by **ChatGPT-4o** and the author through collaborative planning and editing.