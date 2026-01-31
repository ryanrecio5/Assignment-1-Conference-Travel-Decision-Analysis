
# Assignment 01: Conference Travel Decision Analysis

**Student Name:** Ryan Recio  
**Course:** Prescriptive Analytics  
**Assignment:** Assignment 01 – Conference Travel Decision Analysis  

## Overview
This project applies decision framing concepts from Lesson 2 to a real-world business travel planning problem. The goal was to determine the optimal combination of lodging, flights, and team size for attending a 3-night industry conference while staying within a fixed budget and meeting stakeholder priorities.

The analysis uses prescriptive analytics techniques and a PuLP optimization model to balance cost, quality, convenience, and team coverage.

## Key Components
- Clear decision statement defining the controllable choices
- Identification of decision variables vs. inputs
- Distinction between objectives and constraints
- Classification of hard vs. soft constraints
- Tradeoff analysis with visualizations
- Base optimization model
- Updated models incorporating stakeholder considerations

## Stakeholder Considerations
Two additional considerations were incorporated:
1. **Per diem daily allowance for food** (hard budget constraint)
2. **Industry-specific consideration:** avoiding red-eye flights to support productivity and performance

These additions demonstrated how real-world stakeholder needs affect optimal decisions and tradeoffs.

## Files Included
- `assignment_template.ipynb` – Completed Jupyter/Colab notebook with analysis, models, and visualizations
- `README.md` – Project overview and notes

## Notes
- All cells in the notebook are intended to run top-to-bottom without errors.
- The optimization models were built using the PuLP library.
- Data files (`lodging_options.csv` and `flight_options.csv`) are sourced from the course repository and loaded automatically in Google Colab.
- Any assumptions (e.g., per diem amount, quality thresholds) are clearly stated and justified within the notebook.

## Tools Used
- Python
- PuLP
- Pandas
- Matplotlib
- Google Colab
