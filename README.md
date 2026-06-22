# PSX vs. Crypto: Sentiment & Price Transmission Analysis (2025-2026)

This repository contains the complete computational, machine learning, and econometric pipeline developed for a Master's Thesis investigating how international digital asset markets interact with domestic equity valuations in developing economies.

## Project Overview
Using a data pipeline spanning 2025 to 2026, this study isolates the behavioral and financial transmission channels from global crypto ecosystems into the **Pakistan Stock Exchange (PSX KSE-100)**. 

The analytical engine splits the investigation into two distinct dimensions:
1. **The Behavioral Channel:** Natural Language Processing (NLP) sentiment scoring of ~50,000 retail crypto-centric digital texts.
2. **The Capital Channel:** Cross-asset macro price transmission modeling using actual financial historical closing prices.

## Algorithmic & Methodological Structure
The codebase consists of an end-to-end framework organized as follows:
* **Sentiment Extraction:** Leverages **FinBERT** (Financial Bidirectional Encoder Representations from Transformers) to generate a daily composite public sentiment score ranging from -1 to +1.
* **Predictive Machine Learning:** Deploys a **Random Forest Regressor** with non-linear lagged feature matrices to model predictive out-of-sample forecasting variations.
* **Directional Causality:** Computes a multi-lag **Granger Causality Test** to uncover structural time-lagged data pathways.

## Core Empirical Findings

### 1. The Sentiment Detachment (Behavioral)
* **Result:** Descriptive statistics reveal a flat, near-zero Pearson correlation coefficient (-0.064) between daily retail sentiment and PSX returns.
* **Conclusion:** The local Pakistani equity market is completely insulated against global digital asset social media hype.

### 2. The Multi-Day Price Transmission (Macro Capital)
* **Result:** Granger Causality analysis demonstrates high statistical significance across **Lags 1 through 4** ($p < 0.05$).
* **Conclusion:** Actual capital adjustments in the Bitcoin market possess explicit, delayed predictive power over the PSX that ripples sequentially through the Karachi exchange for exactly 4 days before decaying on Day 5.

---
*For questions, methodology replications, or academic citations regarding this dataset, please contact the author or open an Issue in this repository.*
