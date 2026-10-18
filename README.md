# MCDA-Assignment-2

# Logistics Performance Evaluation Using MCDA

**MCDA Assignment 2 | 2026**

## Overview
This project evaluates the logistics performance of 96 economies using six indicators from the World Bank's LPI 2.0 (2024) dataset. It applies three MCDA methods:

- **BWM:** Derives criterion weights from expert judgments.
- **ELECTRE III:** Ranks economies using outranking relationships.
- **ELECTRE TRI-rC:** Classifies economies into five performance classes.

An equal-weight reference ranking is used to compare the results.

## Repository Structure

```text
├── 1.concordance calculations/  # Concordance results
├── 2.discordance calculations/  # Criterion-wise discordance
├── 3.credibility calculations/  # Credibility indices
├── 4. Electre Rankings/         # ELECTRE III ranking
├── 5. Reference Rankings/       # Equal-weight ranking
├── 6. Final Comparison/         # Ranking and classification comparisons
├── 7. electre_tri_rc_fixed_outputs/ # TRI-rC results
├── code/                        # Python Jupyter notebooks
├── data/                        # Input and processed datasets
└── README.md
```

## Key Outputs
- Aggregated BWM criterion weights.
- ELECTRE III economy ranking.
- Equal-weight reference ranking.
- TRI-rC class assignments and intervals.
- Comparisons between rankings and classifications.


## Note
Results depend on expert judgments, model parameters, and implementation assumptions, including the TRI-rC boundary profile \(b_0\).

**Purpose:** Academic coursework for MCDA Assignment 2, 2026.