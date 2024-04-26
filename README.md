# BDC-Optimal-Real-Estate-Investment-Strategy-Analysis

## Project Overview
The Brooks Development Corporation (BDC) Real Estate Project Selection is an optimization case where the corporation faces a strategic decision to invest in a combination of six potential real estate projects. The challenge is to maximize the total Net Present Value (NPV) while operating under a strict budget and a set of constraints.

## Objective
The primary goal is to determine the optimal project combination that yields the highest total NPV, considering the budget of $220 million and specific project interdependencies.

## Constraints
- At least two projects among Projects 1, 3, 5, and 6 must be selected.
- Projects 3 and 5 are to be selected together, if at all.
- Project 4's selection is conditional upon the selection of both Projects 1 and 3.

## Decision Variables
x_i: Binary variable indicating whether Project i is chosen (1) or not (0).

## Mathematical Formulation
The algebraic formulation of the problem maximizes the sum of NPVs of the selected projects subject to the budget constraint and the project interdependency constraints.

## Implementation
The optimization model is implemented in a Jupyter Notebook using Python and employs linear programming techniques for solution finding.

## Results
The optimal investment strategy for BDC is to fully invest in Projects 3 and 5, foregoing Projects 1, 2, 4, and 6. This strategy leads to a total NPV of $33 million, adhering to all budgetary and project constraints.

For a detailed insight into the formulation, implementation, and analysis, refer to the Jupyter Notebook file Real_estate_brooks.ipynb.
