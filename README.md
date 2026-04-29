# ML Portfolio — PM Perspective

**Gunjan Mahesh** | Product Manager building ML fluency

> I build ML models not to do data science — but to make better product decisions using evidence instead of intuition.

---

## Projects

| # | Project | Model type | AUC | Key PM insight |
|---|---------|-----------|-----|----------------|
| 1 | [KKBOX Churn Prediction](./01-kkbox-churn/) | XGBoost Classification | 0.981 | Churn is billing friction, not disengagement. 94% of predictive power from subscription signals, not listening behaviour. |
| 2 | [Credit Card Fraud Detection](./02-fraud-detection/) | XGBoost + Class Imbalance | 0.997 | 96.4% fraud caught. The 9,013 wrongly blocked customers are a PM decision, not a model failure. |
| 3 | Customer Segmentation | K-Means Clustering | — | Coming soon |
| 4 | RFM Segmentation | Clustering | — | Coming soon |
| 5 | Movie Recommendation Engine | Collaborative Filtering | — | Coming soon |
| 6 | Sales Forecasting | Time Series / Prophet | — | Coming soon |
| 7 | Dynamic Pricing | Regression | — | Coming soon |

---

## What each project produces

Every project follows the same structure:

1. **Load and explore data** — understand what signals exist before touching any model
2. **Feature engineering** — create PM-relevant signals from raw data
3. **Train the model** — XGBoost, K-Means, or appropriate algorithm
4. **Evaluate with PM lens** — not just AUC but business impact in users and revenue
5. **Product roadmap** — feature importance becomes a prioritised list of what to build

---

## Skills demonstrated

- XGBoost classification — churn prediction, fraud detection
- Class imbalance handling — scale_pos_weight, precision/recall tradeoffs
- Feature engineering — time-based signals, distance, RFM metrics
- Model evaluation — AUC, F1, confusion matrix, business impact translation
- PM insight extraction — turning feature importance into product roadmaps

---

## Links

- Kaggle profile: [kaggle.com/gunjan9960](https://kaggle.com/gunjan9960)
- KKBOX notebook: [Kaggle link]
- Fraud detection notebook: [Kaggle link]

---

*Built as part of an 11-week ML learning roadmap — April 2026*
