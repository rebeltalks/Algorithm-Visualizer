# Interactive Algorithm Visualizer

An interactive, web-based animation tool designed to help developers and students visualize how popular searching, sorting, and graph traversal algorithms work step-by-step. 

## 🚀 Live Demo & Submission Details

*   **Deployment Link:** [Insert Your Deployment URL Here, e.g., Vercel/Netlify]
*   **Demo Video:** [Insert Link to Screen Recording/Loom Here if running locally]

---

## ✨ Features

*   **Algorithm Selection:** Toggle between 5 core computer science algorithms:
    *   **Sorting:** Bubble Sort, Merge Sort
    *   **Searching:** Binary Search
    *   **Graph Traversal:** Breadth-First Search (BFS), Depth-First Search (DFS)
*   **Playback Controls:** Full state control with **Play ▶️**, **Pause ⏸️**, and **Reset ↻** buttons.
*   **Visual Step Tracking:** Color-coded animations highlighting active elements, comparisons, and final sorted/found states.
*   **Responsive Design:** Clean, modern user interface built for both desktop and mobile viewing.

---

## 🛠️ Tech Stack

*   **Frontend:** HTML5, CSS3, JavaScript (ES6+) / [Optional: React.js / Vue.js / Tailwind CSS]
*   **Animation:** Canvas API / CSS Transitions / [Optional: GSAP]

---

## 💻 Local Setup Instructions

Follow these steps to run the project locally on your machine:

1. **Clone the repository:**
   ```bash
   git clone https://github.com
   ```

2. **Navigate to the project directory:**
   ```bash
   cd YOUR_REPO_NAME
   ```

3. **Launch the application:**
   * If using plain HTML/JS, open `index.html` directly in your browser or use the **Live Server** extension in VS Code.
   * If using a framework (like React):
     ```bash
     npm install
     npm run dev
     ```

---

## 🔍 How It Works

*   **Sorting & Searching:** Array elements are represented as vertical bars. The visualizer updates the DOM dynamically as elements are compared, swapped, or split.
*   **Graph Traversal (BFS/DFS):** A grid or node-link diagram visualizes the discovery and visitation queues, color-changing nodes as they transition from unvisited to processing, and finally to visited.
