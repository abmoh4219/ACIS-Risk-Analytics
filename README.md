# ACIS Risk Analytics

This repository contains code and analysis for AlphaCare Insurance Solutions' risk analytics project. The project focuses on exploratory data analysis (EDA) and predictive modeling of insurance claim data from South Africa, spanning February 2014 to August 2015. The goal is to optimize marketing strategies and identify low-risk segments.

---

## Repository Structure

- **src/**: Source code for analysis and modeling
- **tests/**: Test files
- **models/**: Directory containing saved machine learning models (e.g., `linear_regression_model.pkl`, `random_forest_model.pkl`, `xgboost_model.pkl`).
- **notebooks/**: Jupyter notebook with exploratory data analysis (EDA), hypothesis testing, and predictive modeling.
- **data/**: Datasets (managed with DVC, not pushed to GitHub)
- **.github/workflows/**: CI/CD workflows
- **.gitignore**: Specifies files/folders to ignore (e.g., `data/`, `venv/`)
- **requirements.txt**: Project dependencies

---

## Tasks

1. **Initial Setup**: Git versioning and exploratory data analysis (EDA)
2. **Data Version Control (DVC)**: Setup and configuration
3. **A/B Hypothesis Testing**: 
4. **Stastical Modeling**:
---

## Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/ACIS-Risk-Analytics.git
   python -m venv venv
   python -m venv venv
   source venv/bin/activatepip install -r requirements.txtdvc init
   dvc remote add -d localstorage /tmp/dvc_storagedvc pullvenv\Scripts\activate
   ```
