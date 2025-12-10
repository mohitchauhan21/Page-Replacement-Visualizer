🧠 Efficient Page Replacement Algorithm Simulator

📌 Project Overview

This project is a web-based simulation tool designed to visualize how an Operating System manages memory using Page Replacement Algorithms.

In systems with limited physical memory (RAM), the OS must decide which page to evict to make room for new data. This tool simulates and visualizes three core strategies:

FIFO (First-In, First-Out)

LRU (Least Recently Used)

Optimal (Lookahead Heuristic)

✨ Key Features

Dynamic Visualization: Watch pages move into frames with Green (Hit) and Red (Fault) animations.

Interactive Controls: Pause, Play, and Step-through the simulation cycle by cycle.

Custom Inputs: Enter your own Reference String or generate a random one to stress-test the logic.

Real-Time Analytics: Instantly calculates Page Faults, Hits, and Efficiency Ratios.

Dark Mode UI: A modern, developer-friendly interface built with CSS Grid.

🛠️ Technology Stack

Frontend: HTML5, CSS3 (Keyframe Animations)

Logic: JavaScript (ES6+)

Hosting: GitHub Pages

📖 How to Run Locally

Clone this repository:

git clone [https://github.com/yourusername/Page-Replacement-Visualizer.git](https://github.com/mohitchauhan21/Page-Replacement-Visualizer/edit/main/README.md)

Navigate to the project folder.

Open index.html (or simulator.html) in any web browser (Chrome/Edge/Firefox).

🧩 Algorithms Explained

1. FIFO (First-In-First-Out)

Logic: The oldest page in memory is selected for replacement.

Use Case: Simple to implement but suffers from Belady's Anomaly.

2. LRU (Least Recently Used)

Logic: The page that hasn't been used for the longest time is replaced.

Use Case: Approximates optimal performance by assuming Locality of Reference.

3. Optimal

Logic: Replaces the page that will not be used for the longest period in the future.

Use Case: Theoretical benchmark; impossible to implement in real-time systems.

👥 Contributors

Bhumika Suryawanshi - Frontend & Interface Design

Mohit Chauhan - Backend Logic & Algorithms

This project was built for the Operating Systems Capstone.
