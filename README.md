
# E‑commerce RFM & CLV Analysis 📊

### Problem Statement
Which customer segments drive the most revenue and how can we target them effectively?

### Data
Online retail transactions (Invoice‑level): invoice number, date, customer ID, product, unit price, quantity, country.

### Methodology
1. **Data Cleaning & Feature Engineering** – convert to customer‑level summary  
2. **RFM Scoring** – quintile scores for Recency, Frequency, Monetary  
3. **12‑Month CLV Estimate** – avg order value × purchase rate × 12 months  
4. **Segmentation** – rule‑based tiers (Gold Loyalists, Silver Steady, Bronze Bargain‑Hunters, At‑Risk)  
5. **Geo Analysis** – segment counts by country  
6. **PCA + K‑Means** (optional) – unsupervised validation of segments  

### Key Findings
- **Gold Loyalists** are heavily concentrated in the **United Kingdom (354 customers)**.  
- Top 20 % of customers contribute the bulk of projected revenue → classic 80/20 rule.  
- At‑Risk customers span many countries, highlighting global churn risk.

### How to Run
```bash
git clone <repo-url>
cd ecommerce-rfm-clv
python -m venv venv
source venv/bin/activate      # On Windows: venv\Scripts\activate
pip install -r requirements.txt
jupyter lab notebooks/Notebook.ipynb
```

### Folder Structure
```
ecommerce-rfm-clv/
├── notebooks/
│   └── Notebook.ipynb
├── data/              # raw CSV/XLSX files (gitignored)
├── README.md
├── requirements.txt
├── .gitignore
└── LICENSE
```

### Dependencies
See `requirements.txt`.

### License
MIT – see `LICENSE` file.
