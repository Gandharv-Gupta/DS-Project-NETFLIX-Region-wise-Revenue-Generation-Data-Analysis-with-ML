# 📊 Netflix Revenue Forecasting by Region (2019–2024)

**An end-to-end Machine Learning project** for region-wise revenue analysis and prediction using regression models. Built using Python, MySQL, and key ML libraries to forecast Netflix’s global revenue and identify high-potential markets.

> 📌 *This project is the sole intellectual property of Gandharv Gupta. Dataset sourced from [Kaggle](https://www.kaggle.com/) under open license.*

---

## 🧠 Problem Statement

- Determine **which regions contribute most** to Netflix's **global revenue**.
- Recommend regions with **high potential** for future revenue growth.
- Use **regression modeling and descriptive analysis** to drive business insights.

---

## 🗃️ Dataset

- 📅 Time Period: **2019 to 2024**
- 📁 Format: Flat `.csv` file (unstructured)
- 📌 Target Variable: `Global Revenue`
- 📌 Features:
  - UCAN (US & Canada)
  - EMEA (Europe, Middle East, Africa)
  - LATAM (Latin America)
  - APAC (Asia-Pacific)
  - ARPU (Avg. Revenue Per User per quarter)

---

## 🔧 Tools & Libraries

| Category         | Technologies Used                                   |
|------------------|------------------------------------------------------|
| **Language**     | Python                                               |
| **Data**         | Pandas, NumPy, MySQL                                 |
| **EDA**          | Seaborn, Matplotlib, SciPy                           |
| **Preprocessing**| StandardScaler, Z-Score Normalization                |
| **Modeling**     | Linear, Multiple, and Polynomial Regression          |
| **Evaluation**   | MSE, R², Residual plots, Cross-validation            |

---

## 🧪 ML Workflow

1. **Data Collection**: Loaded raw CSV into Pandas DataFrame.
2. **Preprocessing**:
   - Missing value treatment
   - Z-Score feature scaling
   - Date → Year extraction
   - Currency conversion (USD to Crores)
   - Dropped unnecessary features (e.g., ARPU)
3. **EDA**:
   - Heatmaps, pair plots, box plots, and regression analysis
   - Region-wise revenue trends across years
4. **Modeling**:
   - Trained Linear, Multiple, and Polynomial Regression models
   - Evaluated using `train_test_split`, `R²`, and cross-validation
5. **Insights**:
   - Projected global revenue
   - Identified most/least contributing regions
   - Recommended strategic region focus

---

## 📈 Key Insights

- **EMEA** (Europe, Middle East, Africa) had the **highest contribution** to global revenue.
- **USA & Canada** generated the most revenue individually but ranked lower in global share.
- **APAC** showed consistent growth but remains **underperforming** — a market with high untapped potential.
- Regression models achieved **R² ≈ 0.89**, enabling strong revenue prediction performance.
- All regions showed steady year-over-year revenue increases (except some dips in 2022).

---

## 🧠 Use Cases

- Revenue projection based on regional performance
- Data-driven strategy for market investment and expansion
- Identification of underperforming or high-potential areas

---

## 🧾 Sample Visualizations

- ✅ Heatmaps for correlation analysis
- 📊 Year-over-year box plots
- 📈 Regression and residual plots

---

## 🧮 Evaluation Metrics

| Metric     | Description                        |
|------------|------------------------------------|
| R² Score   | Goodness of fit (≈ 0.89)           |
| MSE        | Mean squared error                 |
| Cross-Val  | 10-fold cross-validation on all models |

---

## 📌 Final Takeaways

- 📍 **EMEA** is the most influential revenue region.
- 📍 **APAC** is underperforming but shows 20%+ potential for growth.
- 📍 Data-driven forecasting can assist Netflix’s market allocation decisions.

---

## 📂 Folder Structure

Netflix-Revenue-Prediction/
├── data/
│ └── netflix_revenue_raw.csv
├── notebooks/
│ └── revenue_analysis.ipynb
├── models/
│ └── final_model.pkl
├── visuals/
│ └── heatmaps, boxplots, etc.
└── README.md

---

## 📣 Disclaimer

> This project is the **sole intellectual property of Gandharv Gupta**. Please credit the author for any reuse or derivative work. The dataset used is publicly available on Kaggle and all rights belong to their respective owners.

---

## 📬 Connect

- 💼 [LinkedIn](https://www.linkedin.com/in/gandharv-guptaofficial/)
- 💻 [GitHub](https://github.com/Gandharv-Gupta)
