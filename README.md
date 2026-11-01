# Artificial Intelligence Lab Repository

**Course Code:** IC-709D / IC-703 C  
**Subject:** Artificial Intelligence Lab  
**Student Name:** Dishan Sheikh  
**Roll Number:** IC-2K23-28  
**Department / Institute:** International Institute of Professional Studies (IIPS), DAVV  

---

## 📌 Repository Overview

This repository contains the complete laboratory curriculum implementations, datasets, models, visualizations, and documentation for the **Artificial Intelligence Lab** as prescribed by the university syllabus.

Each laboratory experiment is structured into dedicated self-contained directories containing:
- Modular, PEP-8 compliant Python source code (`.py`) / Jupyter Notebooks (`.ipynb`)
- Dedicated documentation (`README.md`) with problem statements, algorithms, input/output specifications, execution instructions, and learning outcomes
- Genuine experimental results and generated plots/visualizations

---

## 📂 Directory Structure

```text
IC-2K23-28-AI-Dishan_Sheikh/
├── Lab1/                  # AI Problem Formulation & Intelligent Problem Solving (CO1)
├── Lab2/                  # Heuristic Search Algorithms (CO2)
├── Lab3/                  # AI Programming Frameworks & Data Preparation (CO2, CO5)
├── Lab4/                  # Knowledge Representation & Logical Reasoning (CO1, CO3)
├── Lab5/                  # Machine Learning for Intelligent Decision Making (CO4, CO5)
├── Lab6/                  # Deep Learning Fundamentals using PyTorch (CO4, CO5)
├── Lab7/                  # Explainable AI, Adversarial AI & Advanced Applications (CO4, CO5)
├── datasets/              # Shared datasets used across experiments
├── models/                # Saved models, serialized weights, and checkpoints
├── docs/                  # Flowcharts, architecture diagrams, reports, and analysis
│   ├── algorithm-flowcharts/
│   ├── architecture-diagrams/
│   ├── performance-analysis/
│   └── reports/
├── requirements.txt       # Project dependencies
├── .gitignore             # Standard git exclusions
└── README.md              # Repository overview and documentation
```

---

## 📑 Syllabus & Lab Mapping

| Lab | Topic | Experiments / Core Activities | Course Outcomes |
|---|---|---|---|
| **Lab 1** | AI Problem Formulation & Intelligent Problem Solving | Production Rule Systems, Water Jug Problem, Missionaries & Cannibals Problem, Vacuum Cleaner Problem, State-Space Representation, Rule-based Decision Making | CO1 |
| **Lab 2** | Heuristic Search Algorithms | Generate & Test, Breadth-First Search (BFS), Depth-First Search (DFS), Hill Climbing, Best-First Search, A* Search, 8-Puzzle, Maze Solver, Route Planning | CO2 |
| **Lab 3** | AI Programming Frameworks & Data Preparation | NumPy, Pandas, Matplotlib, Data Cleaning, Missing Value Handling, Label Encoding, Feature Selection, Data Visualization | CO2, CO5 |
| **Lab 4** | Knowledge Representation & Logical Reasoning | Rule-based Representation, Predicate Representation, Semantic Networks, Frames, Conceptual Dependency, Logical Inference Engine | CO1, CO3 |
| **Lab 5** | Machine Learning for Intelligent Decision Making | Feature Matrix Creation, Decision Tree Classifier, Evaluation Metrics, Decision Tree Visualization (Placement, Disease, Loan) | CO4, CO5 |
| **Lab 6** | Deep Learning Fundamentals using PyTorch | Tensors, Autograd, Linear Regression, Neural Network Basics, Loss Functions, Optimizers, Training Loops, Model Evaluation | CO4, CO5 |
| **Lab 7** | Explainable AI & Adversarial AI | Grad-CAM Visualization, Fast Gradient Sign Method (FGSM), ResNet Image Classification, PCA Dimensionality Reduction | CO4, CO5 |

---

## 🛠️ Environment Setup & Installation

### Prerequisites
- Python 3.10+ (Recommended Python 3.11 or 3.12)
- Git

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/<username>/IC-2K23-28-AI-Dishan_Sheikh.git
   cd IC-2K23-28-AI-Dishan_Sheikh
   ```

2. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   # On Windows (Command Prompt / PowerShell):
   .\venv\Scripts\activate
   # On Linux / macOS:
   source venv/bin/activate
   ```

3. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```
