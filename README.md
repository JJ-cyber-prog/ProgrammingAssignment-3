# ECE 2112 - Experiment 3: Python Data Analysis (Pandas)

## Overview
This repository contains the solution for **Experiment 3: Python Data Analysis (Pandas)** for ECE 2112 (Advanced Computer Programming and Algorithms) at the Faculty of Engineering, University of Santo Tomas.

The activity demonstrates the load, selection, filtering, and subsetting operations on tabular data using the `pandas` library without altering the original dataset.

---

## Files Included

- `ECE2112_PA3.ipynb`: The main Jupyter Notebook containing the executable solutions and explanations for Problems A–C.
- `cars.csv`: The dataset containing vehicle attributes (MPG, Cylinders, Horsepower, Weight, etc.).
- `README.md`: Overview and documentation of the repository.

---

## Lab Problems & Tasks Summary

1. **Part A: Positional and Label-Based Slicing**
   - Displays dataset dimensions (`shape`) and column names.
   - Extracts rows 6 through 10 using positional indexing (`.iloc`).
   - Selects specific columns (`Model`, `mpg`, `cyl`, `hp`, `gear`) using label indexing.

2. **Part B: Model Lookup**
   - Retrieves the full record for `Toyota Corolla` using Boolean indexing on the `Model` column.
   - Extracts specific attributes (`Model`, `mpg`, `hp`, `wt`) for `Pontiac Firebird`.

3. **Part C: Multi-Model Subsetting**
   - Filters records for `Datsun 710`, `Lotus Europa`, and `Ferrari Dino` using `.isin()`.
   - Retains only specified columns and validates the subset shape `(3, 5)`.

---

## Dependencies & Requirements

To run the notebook, ensure you have Python 3.x installed along with the required libraries:

- **Python**: 3.8 or higher
- **Pandas**: `pip install pandas`
- **Jupyter Notebook / Lab**: `pip install notebook`

---

## How to Run

1. Clone or download this repository to your local machine.
2. Ensure `cars.csv` is in the same directory as `ECE2112_PA3.ipynb`.
3. Open a terminal or command prompt in the folder directory and run:
   ```bash
   jupyter notebook ECE2112_PA3.ipynb
