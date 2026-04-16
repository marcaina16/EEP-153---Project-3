# EEP 153 – Project 3: Food Demand and Nutrition in Mali

## 📌 Overview
We explore how household wealth levels shape diet composition, nutritional adequacy, and demographic structure in Mali, one of the world's lowest-income countries. Using per-capita food expenditure quartiles from the 2021–22 Mali household survey, we compare bottom- vs. top-quartile households on what they eat, how much nutrition they actually get per CFA spent, and whether the poorest households can mathematically afford a nutritionally adequate diet at Mali's food prices.

---

## 📊 Data
The analysis uses household-level data from Mali, including:

- Food expenditures (2021–2022)
- Household characteristics
- Nutritional content and food prices

All datasets are stored in the `data/` folder.

---

## 📈 Goals
The project includes:

- Estimate a Constant Frisch Elasticity (CFE) food demand system on 6,125 Malian households to recover income elasticities and demographic demand effects
- Compare diet composition and nutrient intensity across per-capita spending quartiles
- Solve for the minimum-cost nutritious diet using linear programming and Mali food prices, then test whether bottom-quartile households can afford it
- Run counterfactual experiments: how would doubling food budgets or halving staple prices affect nutritional adequacy?
- Examine household composition differences across quartiles as a proxy for how fertility and dependent burden interact with food security

All analysis is conducted in Python using Jupyter Notebook.

---
