# AI Governance Gap

This repository contains the code and analysis for a QMSS Master's Thesis at Columbia University, examining how AI risk concern shapes public attitudes toward AI governance in the United States.

## Research Question

Do Americans who worry more about AI want stronger government regulation — and do they trust the government to deliver it?

## Key Findings

- Higher AI concern is associated with stronger support for government regulation (**H1 supported**)
- Higher AI concern is also associated with lower confidence in the government's ability to regulate AI effectively (**H2 supported**)
- Ideology does not moderate the concern-to-regulation relationship (**H3a not supported**)
- Among respondents with the same level of concern, conservatives express lower institutional confidence than liberals, and the gap widens as concern increases (**H3b supported**)

## Data

Pew Research Center American Trends Panel, Wave 152 (August 12–18, 2024), n = 5,410. Nationally representative sample of U.S. adults.

## Methods

Weighted least squares (WLS) regression with HC1 robust standard errors and Pew survey weights. Robustness checks using ordered logistic regression.

## Repository Structure

​```
ai-governance-gap/
├── data/              # Codebook and variable documentation
├── analysis/          # Jupyter notebooks (hypothesis testing, appendix)
├── figures/           # Output figures (Figure 1–3)
└── README.md
​```

## Author

Simona Sun — Columbia University, QMSS Master's Thesis, 2025
