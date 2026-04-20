# 🌐 DFA NEXUS // Minimization Visualizer

<div align="center">
  <p><strong>Advanced Interactive Partition Refinement Simulation</strong></p>
  
  [![React](https://img.shields.io/badge/React-18.x-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://reactjs.org/)
  [![Tailwind CSS](https://img.shields.io/badge/Tailwind-CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
  [![Framer Motion](https://img.shields.io/badge/Framer_Motion-black?style=for-the-badge&logo=framer&logoColor=blue)](https://www.framer.com/motion/)
  [![License: MIT](https://img.shields.io/badge/License-MIT-emerald.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)
</div>

---

## 💻 System Overview

**DFA NEXUS** is a high-fidelity, interactive educational tool designed to visualize the step-by-step minimization of Deterministic Finite Automata (DFA). Built with a futuristic, glassmorphic UI, it breaks down complex theoretical computer science algorithms—specifically partition refinement (Myhill-Nerode / K-Equivalence)—into cinematic, digestible visual simulations.

Whether you are synthesizing an optimal state machine architecture or exploring automata theory, this visualizer provides real-time telemetry on state equivalence and node merging.

---

## ✨ Core Modules

### 1. 🎬 Live Simulation Matrix
Define your own state matrix, input alphabet, boot nodes, and transition rules. Watch the algorithm auto-sequence through:
* **Dead Code Pruning:** Elimination of unreachable states.
* **0-Equivalence:** Initial partitioning into accepting/rejecting clusters.
* **K-Equivalence:** Iterative refinement and splitting of distinguishable states.
* **Magnetic Fusion:** Fluid visual merging of equivalent states into the final optimal architecture.

### 2. 📚 Academy Databanks (Learning Mode)
A structured, interactive textbook side-panel that syncs with a live graph. It explains the core objectives of DFA optimization, guiding users through the theory behind state minimization step-by-step.

### 3. 🎯 Protocol Assessment (Quiz Mode)
Test your theoretical knowledge. Analyze different DFA matrices to identify unreachable states, structurally equivalent nodes, and predict final optimization counts.

---

## 🛠️ Technical Stack

This application is architected for zero-build-step deployment, utilizing in-browser compilation for rapid prototyping:
* **Core:** React 18 & ReactDOM (via CDN)
* **Compiler:** Babel (In-browser JSX parsing)
* **Styling:** Tailwind CSS (via CDN) with custom CSS glassmorphism & animated grid layouts.
* **Animation Engine:** Framer Motion for layout transitions, layout grouping, and fluid presence animations.
* **Graph Visualization:** Vis-Network (vis.js) for high-performance, physics-based node clustering and dynamic self-loop routing.

---

## 🚀 Deployment Guide (GitHub Pages)

Because this project is contained within a single, powerful `index.html` file using CDN resources, deploying it to the web is incredibly fast. 

### Step 1: Initialize the Repository
1. Create a new repository on your GitHub account (e.g., `dfa-nexus-visualizer`).
2. Clone it locally or upload directly via the GitHub UI.
3. Ensure your main visualizer file is named exactly `index.html` and is located in the root directory.

### Step 2: Push to GitHub
If using the terminal:
```bash
git init
git add index.html
git commit -m "INIT: Deploy DFA Minimizer Visualizer"
git branch -M main
git remote add origin [https://github.com/YOUR_USERNAME/dfa-nexus-visualizer.git](https://github.com/YOUR_USERNAME/dfa-nexus-visualizer.git)
git push -u origin main

Website - https://fallencronus-ui.github.io
