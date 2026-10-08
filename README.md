# ANALYSTAA (AnalySta): AI-Powered Stock Analysis Dashboard

AnalySta is a stock analysis and prediction web dashboard. It presents LSTM-based stock predictions, sentiment insights (FinBERT), and SHAP-explained Buy / Hold / Sell signals through an interactive frontend.

📄 **Research paper:** *AnalySta: AI-Powered Stock Analysis Predict and Investment System*, IJARESM, Vol. 13(4), 2025

---

## Features

- Dashboard for stock predictions and trends
- Sentiment insights from news and social data
- Buy / Hold / Sell investment signals
- Investment calculator
- Multi-page UI (homepage, login, analytics pages)

## About the Model 

- LSTM model trained on 37 technical indicators
- 4 FinBERT-derived sentiment indicators
- LASSO-based feature selection
- SHAP explainability for feature-level interpretation of each signal

## Tech Stack

HTML, CSS, JavaScript (frontend) | Python, TensorFlow, LSTM, FinBERT, SHAP (model, described in the paper)

## Project Structure

```
ANALYSTAA/
├── css/          # Stylesheets
├── html/         # Dashboard and app pages
├── image/        # Images and assets
├── js/           # Frontend logic
├── video/        # Media assets
├── index.html    # Homepage (entry point)
└── README.md
```
