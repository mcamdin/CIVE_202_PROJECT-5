# Steel Beam Analysis Code (Project #5 – CIVE 202)

## Overview  
This project focuses on creating a Python-based tool to analyze steel beams and check whether they meet basic design requirements. The goal was to take concepts from class (like loads, reactions, and moments) and turn them into code that can automatically evaluate a beam.

Instead of solving everything by hand, this code lets the user input values (like loads and beam properties) and get results quickly. It’s meant to show how coding can be used in civil engineering to make calculations more efficient and consistent.

---

## What the Code Does  
- Takes user inputs for beam properties (length, loads, etc.)  
- Calculates reaction forces at supports  
- Determines shear forces and bending moments  
- Checks if the beam is acceptable based on given conditions  
- Outputs results in a way that’s easy to understand  

---

## Files Included  
- `Project#5.ipynb` → Main Jupyter Notebook with all code and explanations  
- `README.md` → This file explaining the project  

---

## How to Run the Code  
1. Open the notebook in Jupyter Notebook or JupyterLab  
2. Run each cell from top to bottom  
3. Enter the required inputs when prompted  
4. View the outputs and results printed below each section  

---

## Code Structure  
The notebook is organized into sections:

- **Input Section** → defines beam length, loads, and other properties  
- **Calculation Section** → functions that compute reactions, shear, and moments  
- **Evaluation Section** → checks whether the beam meets requirements  
- **Output Section** → prints results clearly  

Each part is commented so it’s easy to follow what the code is doing.

---

## Key Concepts Used  
- Static equilibrium (ΣF = 0, ΣM = 0)  
- Shear force and bending moment relationships  
- Basic structural behavior of beams  
- Python functions and conditional logic  

---

## Assumptions  
- Beam is analyzed under simplified loading conditions  
- Loads follow standard statics assumptions  
- A safety factor is included since one was not explicitly provided  

---

## Why This Project Matters  
This project shows how coding can be used in civil engineering to automate repetitive calculations and reduce human error. It connects concepts from statics to real-world structural analysis.

---

## Possible Improvements  
- Add more complex loading cases  
- Include different beam types (cantilever, continuous, etc.)  
- Generate shear and moment diagrams  
- Turn into a simple user interface or web tool  

---

## Author  
Camdin Wagner McGuigan  
CIVE 202 – Civil Engineering
