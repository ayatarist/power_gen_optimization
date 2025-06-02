# Power Generation Optimization Model

**Author:** Aya Tarist  
**Date:** August 2023  
**Notebook:** [Power Generation Optimization Model.ipynb](Power%20Generation%20Optimization%20Model.ipynb)

---

## 📖 Overview

This Jupyter notebook implements two related optimization formulations for a small power‐generation portfolio:

1. **Model 1 (Linear Programming):**  
   A continuous (LP) formulation that minimizes the total variable cost of electricity production across a set of generators (coal, natural gas, solar, wind) over a 24-hour horizon.

2. **Model 2 (Mixed-Integer Programming):**  
   A mixed-integer version that introduces “on/off” binary status variables for each generator (to capture startup/shutdown decisions, minimum run constraints, and fixed costs). The objective still minimizes total production cost (variable plus fixed), subject to demand, CO₂ limits, and minimum‐renewables requirements.

---

## 🛠️ Technologies & Dependencies

- **Python 3.x**  
- **Gurobi** (≥ 9.0)  
- **pandas** (≥ 1.0)  
- **matplotlib** (for plotting results)  
- **Jupyter Notebook** (to run, view, and modify the model)

To install dependencies via `pip`, you might run:

```bash
pip install gurobipy pandas matplotlib jupyter
