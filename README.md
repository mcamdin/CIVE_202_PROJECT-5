# Project 5 – Automated Design and Evaluation of W-Shaped Steel Tension Members

## Overview

This project was completed for CIVE 202 and focuses on automating the design check process for W-shaped steel tension members using Python. The notebook loads cleaned W-beam data, calculates allowable strengths using safety factors, and determines if selected steel members can safely resist applied tension loads.

The goal of this project was to create a simple engineering tool that can quickly evaluate different W-shape beams without needing to complete repetitive hand calculations every time.

---

## Project Objectives

* Import and clean W-shape beam data from a CSV file
* Calculate allowable yield strength
* Calculate allowable fracture strength
* Determine the governing strength of each beam
* Allow user input for custom beam checks
* Test multiple design scenarios
* Create graphs to compare loads and strengths
* Organize the code in a clean and readable notebook format

---

## Packages Used

The following Python packages were used in this project:

* pandas
* numpy
* plotly

These packages were used for data handling, calculations, and graph visualization.

---

## Engineering Concepts Used

This project uses basic steel tension member design concepts commonly used in civil and structural engineering.

The program calculates:

* Allowable Yield Strength
* Allowable Fracture Strength
* Governing Strength

Safety factors were included in the calculations to create more realistic design results.

### Safety Factors Used

* Yield Safety Factor = 1.67
* Fracture Safety Factor = 2.00

---

## Notebook Sections

The notebook is organized into several sections:

1. Import Packages
2. Load and Check Beam Data
3. Set Safety Factors
4. Calculate Yield and Fracture Strengths
5. Determine Governing Strength
6. Create Beam Check Function
7. User Input Design Check
8. Client Design Scenarios
9. Results Tables
10. Graphs and Visualization

---

## User Input Function

The notebook includes a function where the user can enter:

* W-shape beam
* Yield strength (Fy)
* Fracture strength (Fu)
* Applied tension load

The program then determines if the selected beam is acceptable based on the governing allowable strength.

Example:

```python
shape = "W24x55"
Fy = 50
Fu = 65
load = 500
```

---

## Graphs Included

Two graphs were created using Plotly:

1. Applied Load vs Governing Strength
2. Yield Strength vs Fracture Strength

These graphs help visualize how the applied loads compare to the allowable member strengths.

---

## Files Included

* `Project#5.ipynb` → Main Python notebook
* `Project5_W_Beams.csv` → Cleaned W-shape beam dataset
* `README.md` → Project explanation and overview

---

## Results

The project successfully:

* Loaded and analyzed over 200 W-shape beams
* Calculated allowable strengths automatically
* Checked multiple beam scenarios
* Compared design loads against governing strengths
* Generated engineering graphs for visualization

The notebook can be expanded in the future to include compression members, bending checks, or additional structural calculations.

---

## Author

Camdin Wagner McGuigan and Ahmad Rezaie
CIVE 202 – Civil Engineering Coding Project
University of Nebraska
