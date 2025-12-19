# AI Search Algorithm Visualizer 

**Course:** CS-415 Artificial Intelligence  
**Assignment:** #1 - Implementation of Search Strategies  
**Student:** Hamza Chohan

## 📖 About The Project
This project is a web-based visualization tool developed to demonstrate the working mechanisms of fundamental Artificial Intelligence search algorithms. It models a country map as a graph of **cities (nodes)** and **roads (weighted edges)** and allows users to visualize how different algorithms traverse the map to find a path from a start point to a destination.

The project was built using **HTML5 Canvas** and **Vanilla JavaScript** to ensure high performance and easy accessibility without requiring backend servers.

## 📸 Interface Preview
![Project Screenshot](1.jpg)
![Project Screenshot](2.jpg)
![Project Screenshot](3.jpg)

## 🚀 Features
* **Interactive Controls:** Select any Origin and Target city dynamically.
* **Algorithm Support:**
    * **BFS (Breadth-First Search):** Explores layer-by-layer (Finds fewest hops).
    * **DFS (Depth-First Search):** Explores deep paths first.
    * **UCS (Uniform Cost Search):** Explores based on lowest cumulative cost (Finds the cheapest path).
* **Animation Engine:**
    * **Playback Speed:** Adjustable speed slider (100ms - 1500ms) to watch the "thinking" process.
    * **Step Mode:** Manually step through the algorithm node-by-node for debugging.
    * **Play/Pause:** Pause the search at any moment.
* **Real-Time Metrics:** Displays the total **Traversal Cost** and **Time Complexity (Steps taken)** instantly.
* **Visual Feedback:** Color-coded graph showing explored nodes (Orange), active path (Teal), and standard connections.

## 🛠️ Technologies Used
* **HTML5 / CSS3:** Custom Dark Theme dashboard.
* **JavaScript (ES6+):** Core logic for graph traversal and state management.
* **HTML Canvas API:** Used for drawing the dynamic nodes and lines.

## ⚙️ How to Run
Since this project relies on static web technologies, no installation or server (like XAMPP) is required.

**Option 1: Run Locally**
1.  Clone or download this repository.
2.  Locate the `index.html` file.
3.  Double-click to open it in any modern web browser (Chrome, Edge, Firefox).

**Option 2: Live Demo**
* [Insert your GitHub Pages Link Here]

## 🧠 Algorithm Analysis
This tool helps visualize the differences between the algorithms:
* **BFS** is optimal for unweighted graphs but fails to consider road costs in this map scenario.
* **DFS** is memory efficient but often takes non-optimal, winding paths.
* **UCS** guarantees the lowest cost path by accounting for edge weights, making it the best choice for this specific problem.

---
*Developed by Hamza Chohan for CS-415*
