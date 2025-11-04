# Influenza Trends Analysis & Forecasting

This repository contains a data analysis project examining influenza-like illness (ILI) trends in the United States and forecasting future influenza activity using time-series modeling.

The findings are based on CDC ILI surveillance data and supporting clinical datasets.

---

## 📂 Project Files

| File | Description |
|------|------------|
`Analyzing_Influenza_Trends_revised_final_v.ipynb` | Main analysis notebook (data cleaning, visualization, forecasting)
`ILINet.csv` | CDC ILI data
`ICL_NREVSS_Clinical_Labs.csv` | Clinical lab dataset
`ICL_NREVSS_Public_Health_Labs.csv` | Public health lab dataset
`influenza_outbreak_dataset.mat` | Historical flu monitoring dataset
`Original Work.pdf` | Old Coursework reference / documentation

---

## 📊 Key Objectives

- Identify seasonal patterns in influenza activity
- Compare influenza severity across U.S. regions
- Build and evaluate a time-series forecasting model
- Visualize historical trends and projection uncertainty

---

## 🧠 Highlights & Insights

- ILI peaks in **late December**, reflecting typical U.S. winter seasonality
- Summer values reach the **lowest plateau**, followed by early-fall rebound
- Southern states (e.g., Alabama, Texas, Louisiana) show **higher severity levels**
- Forecast captures the seasonal transition, with uncertainty increasing over time

---

## 🛠️ Tools & Libraries

- Python, Jupyter Notebook
- `pandas`, `numpy`, `matplotlib`, `seaborn`
- `statsmodels` (ARIMA forecasting)

---

## 🚀 How to Run

```bash
# clone the repo
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>

# open notebook
jupyter notebook Analyzing_Influenza_Trends_revised_final_v.ipynb
