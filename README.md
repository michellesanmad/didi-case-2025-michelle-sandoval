# DiDi Take-Home Case – Data Analyst Intern

This repository contains the solution to the take-home case study assigned as part of the recruitment process for the Data Analyst Intern position at DiDi Chuxing Technology Co.

## 📁 Project Structure
didi-case-2025/
│
├── data/                      # Raw and cleaned data files (CSV)
│
├── notebooks/                 # Jupyter Notebooks with analysis and modeling
│   ├── 01_eda.ipynb           # Exploratory Data Analysis
│   ├── 02_queries.ipynb       # SQL queries and validation
│   ├── 03_validation.ipynb    # Metrics and testing
│   ├── 04_modeling.ipynb      # Forecasting with Prophet
│   └── 05_forecast.ipynb      # Forecasting with LSTM (TensorFlow/Keras)
│
├── figures/                   # Automatically generated plots from models
│   ├── forecast_plot.png          # Plot showing historical and forecasted values
│   └── training_history.png       # Loss curve of LSTM model (train vs validation)
│
├── requirements.txt           # Project dependencies
├── README.md                  # Project documentation and explanations
└── .venv/                     # Local Python virtual environment (not versioned)

## 📊 Progress

- [x] Data loading and initial EDA
- [x] Business question answers
- [x] Visualizations
- [ ] Final polish and documentation

## 🛠️ Environment

This project runs on:
- Python 3.9
- Pandas, Matplotlib, Jupyter
- VS Code (recommended)

## 📊 Key Visuals

| Image | Insight |
|-------|---------|
| `training_history.png` | Model loss converges by epoch ~40 → no sign of over-fitting. |
| `forecast_plot.png`    | Shows historical daily visitors (blue) and the 180-day LSTM forecast (orange). |


### 🔧 Setup instructions
> ⚠️ Notes: Raw CSV files are excluded from the repository (see `.gitignore`). Please place your raw data in `data/raw/` to reproduce the results.
.venv/ is not included in the repository. You must create it locally using:

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt

🤝 Author
Michelle Sandoval Madrigal
Data Analyst Intern Candidate @ DiDi

---