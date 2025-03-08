# Fuzzy AHP-TOPSIS Decision Model for Project ROI Optimization

## Overview
This repository contains datasets and a Python script implementing **Fuzzy AHP-TOPSIS**, an advanced **multi-criteria decision-making (MCDM)** framework for optimizing **return on investment (ROI) in project management**.

## Files Included
- **decision_matrix.csv** - Fuzzy evaluation of project alternatives across criteria.
- **criteria_weights.csv** - Fuzzy AHP-derived criteria weight assignments.
- **ranking_results.csv** - Final rankings of project alternatives using Fuzzy TOPSIS.
- **fuzzy_ahp_topsis_code.py** - Python script implementing the Fuzzy AHP-TOPSIS methodology.
- **README.md** - Documentation explaining the dataset and script usage.

## Methodology
This study applies a **hybrid Fuzzy AHP-TOPSIS approach** for investment decision-making:
1. **Fuzzy AHP** - Used for expert-driven criteria weighting via fuzzy pairwise comparisons.
2. **Fuzzy TOPSIS** - Ranks alternatives based on their similarity to an ideal project investment.
3. **Sensitivity Analysis & Rank Reversal Test** - Validates ranking stability and robustness.

## How to Use
### 1️⃣ Install Dependencies
Ensure you have **Python 3.x** installed, then install required libraries:
```bash
pip install numpy pandas
