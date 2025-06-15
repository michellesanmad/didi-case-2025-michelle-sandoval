# DiDi Take-Home Case – Data Analyst Intern

This repository contains the solution to the take-home case study assigned as part of the recruitment process for the Data Analyst Intern position at DiDi Chuxing Technology Co.

## 📁 Project Structure
```text
├── data/ # Raw and processed datasets
├── notebooks/ # notebooks EDA, SQL query validation, forecasting
├── sql/ # .txt files with SQL queries
├──figures/ # Output plots from forecasting model
├── slides/ # Final presentation
└── README.md # Project overview and usage
```

## 📊 Progress

- [x] Data loading and initial EDA
- [x] Business question answers
- [x] Visualizations
- [x] Final polish and documentation

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

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## 🤝 Author
Michelle Sandoval Madrigal

Data Analyst Intern Candidate @ DiDi

---