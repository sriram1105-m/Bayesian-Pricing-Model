# Bayesian Pricing Model for Facilities Management

### 🧠 Goal
Build an end-to-end, production-style pricing model to predict energy margins across FM sites — with business-awareness, risk flags, and uncertainty.

---

### 🛠 Dataset
- Simulated energy usage for 6 months across multiple asset types
- Includes time features, occupancy, cost, billing rate, and margin

---

### 📊 Key Features
- Business-driven feature engineering (OOH flag, volatility, margin ratio)
- Bayesian regression model with uncertainty
- Risk flagging for low-margin predictions
- Hourly and asset-type level margin analysis
- Power BI dashboard via Azure Blob output

---

### 🪜 Pipeline
1. **Data Cleaning** → remove inconsistencies, nulls, skewed values
2. **EDA** → margin trends, risk patterns, hourly/asset impact
3. **Feature Engineering** → volatility, flags, ratios
4. **Modeling** → Bayesian Ridge with MAP estimates
5. **Deployment** → Azure Blob + Power BI for business interface

---

### 📈 Dashboard
![dashboard](powerbi_screenshot.png)

---

### 🧩 Files
| File | Description |
|------|-------------|
| `notebooks/` | All modular Jupyter steps |
| `predicted_margins.csv` | Final predictions |
| `bayesian_model.pkl` | Trained model object |
| `powerbi_screenshot.png` | Dashboard snapshot |

---

### 🚀 Author Notes
This was designed to simulate a real job use case using sample data from my prior FM project — not just ML accuracy but business impact and decision readiness.
