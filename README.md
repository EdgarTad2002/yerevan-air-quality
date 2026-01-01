# Yerevan Air Quality Analysis (PM2.5)

This project analyzes **PM2.5 air pollution levels in Yerevan** using open, publicly available air-quality data.
The goal is to explore temporal patterns, identify extreme pollution days, and build a regression model to better understand factors influencing air quality.

Air pollution, especially PM2.5, is a major public health concern, and this analysis aims to provide data-driven insights into pollution behavior in Yerevan.

---

## 📊 Dataset

The dataset is downloaded **directly within the notebook** from the official ArmeniaBlackouts.org data repository.
No local data files are required.

**Data Source:**  
https://armeniablackouts.org

We acknowledge **ArmeniaBlackouts.org** as the data provider.

---

## 🔍 Project Scope & Analysis

The notebook includes:

- **Exploratory Data Analysis (EDA)**
  - Distribution of PM2.5 values
  - Missing data inspection
- **Temporal Analysis**
  - Daily and seasonal patterns
  - Long-term trends
- **Extreme Pollution Days**
  - Identification of high-PM2.5 events
  - Frequency and severity analysis
- **Regression Modeling**
  - Predicting PM2.5 levels using available features
  - Model evaluation and interpretation

---

## 🛠️ Tech Stack

- Python
- pandas
- numpy
- matplotlib / seaborn
- scikit-learn
- Jupyter Notebook

---

## ⚠️ Limitations

- Data quality depends on sensor availability and reliability.
- The regression model is intended for **exploratory analysis**, not operational forecasting.
- External factors (traffic, weather, policy changes) may not be fully captured.

---

## 🚀 Future Improvements

- Integrate weather data for improved prediction accuracy
- Add time-series models (ARIMA, SARIMA)
- Build an interactive dashboard (Streamlit / Django)
- Automate daily data updates

---

## ▶️ Setup Instructions

```bash
git clone <repo_link>
cd yerevan-air-quality
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
jupyter notebook



