# 🌲 Forest Fire Risk Assessment
**Forest Fire Risk Assessment** is a Python-based machine learning project that uses **Multivariate Linear Regression (MLR)** to predict the burned area of forest fires based on meteorological and environmental factors from the Algerian Forest Fires Dataset.

**Disclaimer**: For educational and analytical purposes only. Not intended for operational fire management decisions.

## Overview
An end-to-end regression pipeline that analyzes environmental variables such as temperature, humidity, wind speed, and rainfall to estimate wildfire severity — providing data-driven insights for environmental risk management and disaster response planning.

## Key Features
- Predicts forest fire burned area from meteorological & environmental inputs
- Multivariate Linear Regression with full preprocessing pipeline
- Exploratory Data Analysis with visual insights
- Model evaluation using MAE, MSE, RMSE, and R² metrics
- Clean Flask web interface for real-time predictions
- Reproducible Jupyter notebooks for the complete ML workflow

## Tech Stack
<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white" alt="Flask"/>
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white" alt="Scikit-Learn"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="Pandas"/>
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" alt="NumPy"/>
  <img src="https://img.shields.io/badge/Matplotlib-11557C?style=flat-square&logo=python&logoColor=white" alt="Matplotlib"/>
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white" alt="Jupyter"/>
</p>

## Installation

Install:
- **Git**: [Download](https://git-scm.com/download/win)
- **Python 3.8+**: [Download](https://www.python.org/downloads/)

### Clone Repository
1. Open CLI.
2. Run:
   ```bash
   git clone https://github.com/KaustubhMestri/Forest-Fire-Risk-Assessment
   cd Forest-Fire-Risk-Assessment
   ```

### Set Up Environment
1. Create a virtual environment:
   ```bash
   python3 -m venv venv
   ```
2. Activate:
   ```bash
   source venv/bin/activate
   ```
3. Install dependencies:
   ```bash
   pip install -r requriements.txt
   ```

### Run App
```bash
python app.py
```
Open `http://127.0.0.1:5000`.

## Dataset
The model is trained on the **Algerian Forest Fires Dataset**. Input features include meteorological indicators such as `Temperature`, `Relative Humidity (RH)`, `Wind Speed (Ws)`, `Rain`, and FWI (Fire Weather Index) system components: `FFMC`, `DMC`, `DC`, `ISI`, `BUI`, and `FWI`. The target variable is the **burned area** (hectares).

## Contributing
1. Create an [issue](https://github.com/KaustubhMestri/Forest-Fire-Risk-Assessment/issues).
2. Branch: `feature/<n>` or `bugfix/<n>`
   ```bash
   git checkout -b feature/<n>
   ```
3. Commit:
   ```bash
   git add .
   git commit -m "#<issue> message"
   ```
4. Push:
   ```bash
   git push origin feature/<n>
   ```
5. Submit PR to `main`.

## License
MIT License. See [LICENSE](LICENSE).
