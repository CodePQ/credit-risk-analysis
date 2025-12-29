# Credit Risk & Default Probability Modeling

## Project Overview
This project builds an interpretable credit risk model to estimate the probability of default and support lending decisions under uncertainty. The emphasis is on decision support, interpretability, and cost-sensitive evaluation rather than maximizing predictive accuracy alone.

## Business Problem
Financial institutions must balance loan approval rates against default risk. Poorly calibrated or opaque models can lead to excessive losses or overly conservative lending. This project focuses on modeling default risk in a way that is transparent, auditable, and aligned with real-world lending tradeoffs.

## Data
The analysis uses the publicly available "Default of Credit Card Clients" dataset from the UCI Machine Learning Repository. The dataset contains borrower demographics, credit limits, repayment history, bill amounts, and payment behavior, along with a binary indicator of default in the following month.

## Methodology (Planned)
The project follows a disciplined workflow:
- Structural and semantic exploratory data analysis (completed)
- Feature type classification based on domain knowledge
- Interpretable baseline modeling using logistic regression
- Evaluation under class imbalance using ROC and precision–recall metrics
- Threshold-based decision analysis reflecting asymmetric error costs

## Current Status
- Raw data ingestion and validation completed
- Target variable and class imbalance assessed
- Feature types classified (continuous, ordinal, categorical)
- No preprocessing, encoding, or modeling performed yet

## Notes
This model is intended as a decision-support tool and does not replace human judgment. Dataset limitations and ethical considerations will be explicitly discussed.
