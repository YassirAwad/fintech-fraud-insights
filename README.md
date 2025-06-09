# fintech-fraud-insights
# Credit Card Fraud Detection with Explainability 

This project applies machine learning to detect fraudulent credit card transactions using the [Kaggle Credit Card Fraud Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud). It includes interpretability using SHAP and a Power BI dashboard for visual analytics.

📁 Project Structure

- `notebooks/` – Jupyter notebooks for exploration, modeling, and explainability
- `src/` – Python scripts for reusable code (e.g., preprocessing, model training)
- `data/` – Contains the dataset (add `.gitignore` entry if too large)
- `reports/` – Power BI dashboard and report summaries
- `visuals/` – SHAP plots, confusion matrices, etc.
- `requirements.txt` – Python dependencies

🔍 Tools & Technologies

- Python (pandas, scikit-learn, imbalanced-learn, SHAP)
- Power BI
- Jupyter Notebooks

📊 Explainability

We use **SHAP** to explain model predictions, showing which features contribute most to identifying fraud.

📈 Dashboard

The Power BI dashboard provides:
- Fraud vs Non-Fraud trends
- SHAP-based feature importance visuals
- Time-based analysis of fraudulent transactions

🚀 Getting Started

1. Clone the repo:
```bash
git clone https://github.com/YassirAwad/credit-card-fraud-detection.git

