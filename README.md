# Fintech Fraud Detection & Analytics (50,000 Nigerian Transactions) 

[Dashboard Preview](https://ibb.co/PzGnLbL3)

Real-world Nigerian fintech fraud detection & analytics system built from scratch using a fully synthetic, realistic 50,000-transaction dataset  
Detects fraud using *velocity, channel risk, amount thresholds, merchant scoring* — exactly how Opay, Moniepoint & Kuda do it.

## Key Features
- 50,000 realistic Nigerian transactions (2024–2025)
- 5,000 customers | 200 merchants
- 8+ real fraud detection rules (velocity, USSD abuse, reversal patterns)
- RFM customer segmentation
- Monthly active users & churn tracking
- High-risk merchant exposure
- All in *pure SQL + Python (pandas + SQLite)*

## Fraud Detection Rules Implemented
| Rule                  | Detection Rate |
|-----------------------|----------------|
| High amount (>₦1.5M)  | Very High      |
| USSD >₦800k           | Very High      |
| 8+ txns in 10 mins    | Extremely High |
| High-risk merchants   | High           |

## Tech Stack
- Python · Pandas · SQLite · Matplotlib/Seaborn
- 100% reproducible · No API keys

## How to Run
```bash
# Just open the notebook and run all cells
jupyter notebook Fintech_Fraud_Analytics.ipynb

Built to show recruiters:
“I don’t just know SQL — I catch fraud like a Nigerian fintech pro.”
Nigeria | Fintech | Fraud Detection | SQL | Data Analytics | Portfolio Project
⭐ Star if you’re building the future of African fintech.
