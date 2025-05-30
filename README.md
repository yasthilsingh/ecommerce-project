
# E‑commerce RFM & CLV Analysis 📊

This project explores how to segment customers based on Recency, Frequency, and Monetary (RFM) behavior and estimate their Customer Lifetime Value (CLV). It helps identify the most valuable customer segments and suggest strategies for retention and growth.

👉 **Live GitHub Pages Demo**:  
View the interactive analysis and visualizations here:  
🔗 [https://yasthilsingh.github.io/ecommerce-project/](https://yasthilsingh.github.io/ecommerce-project/)

🧠 **Want to see the code?**  
You can explore the full Jupyter Notebook in this repository:  
[Notebook.ipynb](Notebook.ipynb)

---

### 📌 Problem Statement

Which customer segments drive the most revenue and lifetime value, and how can we target these high-value cohorts effectively?

---

### 📊 Data

- Invoice-level retail data including:
  - Invoice number, date, customer ID
  - Product, unit price, quantity, country

---

### 🧪 Methodology

1. **Data Cleaning & Feature Engineering** – Convert to customer-level summary
2. **RFM Scoring** – Assign quintile scores to Recency, Frequency, Monetary features
3. **12-Month CLV Estimation** – Based on purchase rate and average order value
4. **Customer Segmentation** – Rule-based persona labeling (Gold Loyalists, At-Risk, etc.)
5. **Country-wise Distribution** – Rank segments by geography
6. **Optional**: PCA + Clustering to validate behavioral groupings

---

### 💡 Key Findings

- Gold Loyalists are most concentrated in the United Kingdom.
- A small number of customers account for the majority of projected revenue (Pareto insight).
- At-Risk customers appear across multiple regions — a clear opportunity for retention campaigns.

---

### 🔧 How to Run Locally

```bash
git clone https://github.com/yasthilsingh/ecommerce-project.git
cd ecommerce-project
pip install -r requirements.txt
jupyter lab Notebook.ipynb
```

---

### 🗂 Folder Structure

```
ecommerce-project/
├── docs/            # GitHub Pages HTML version
│   └── index.html
├── Notebook.ipynb     # Full analysis with code and markdown
├── README.md
├── requirements.txt
├── .gitignore
```

---

### 📬 Contact

For questions or collaboration, feel free to connect via LinkedIn or GitHub.
