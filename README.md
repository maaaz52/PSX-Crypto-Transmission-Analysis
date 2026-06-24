# Comparison between PSX and Crypto: Sentiment and Price Transmissions (2025-2026)

This repository holds the entire computational, machine learning and econometrics pipeline created for research analyzing the relationship between international cryptocurrency markets and the valuation of domestic equities in emerging countries.

## Project Description
Based on a data pipeline covering 2025 to 2026, this research focuses on behavioral and financial transmissions from international cryptocurrency ecosystems into the **Pakistan Stock Exchange (PSX KSE-100)**.

The analytical pipeline breaks down the research into two separate streams:
1. **Behavioral Channel:** The NLP sentiment scoring of ~50,000 crypto-based digital content.
2. **Capital Channel:** Macro price transmissions between assets with actual financial historical closing prices.

## Algorithmic & Methodological Structure
The codebase includes an end-to-end pipeline structured as follows:
* **Sentiment Extraction:** Using **FinBERT** (Financial Bidirectional Encoder Representations from Transformers) to compute a daily composite public sentiment score between -1 and +1.
* **Predictive Machine Learning:** Using a **Random Forest Regressor** with non-linear lagged feature matrixes to predict variations out-of-sample.
* **Causality Detection:** Computing multi-lag **Granger Causality Test** to discover structural time-lagged paths in the data.
## Primary Empirical Results

### 1. The Sentiment Decoupling (Behavioral)
* **Conclusion:** Descriptive statistics indicate that the relationship between daily retail sentiment and PSX returns is characterized by an almost zero Pearson correlation coefficient (-0.064).
* **Inference:** The Pakistani stock market is perfectly shielded from the influence of international crypto social media buzz.

### 2. The Multi-Day Price Propagation (Macro Capital)
* **Conclusion:** The Granger Causality test indicates significant statistical correlation at the **lags of 1 to 4 days** ($p<0.05$).
* **Inference:** The actual capital moves in the Bitcoin market have specific delayed predictive value on the PSX that propagates successively over 4 days in the Karachi stock exchange.

---
*In case of any inquiries related to this data set, please feel free to reach out to the author or create an Issue here.*
