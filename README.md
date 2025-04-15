# Teco Customer Churn Analysis

## Project Overview
This project performs an exploratory data analysis (EDA) on the Teco Telecom customer dataset to identify key factors influencing customer churn. The goal is to uncover insights that inform targeted retention strategies.

## Dataset
- **Source:** Teco Telecom customer records
- **Features include:**
  - `customerID`, `gender`, `SeniorCitizen`, `Partner`, `Dependents`
  - `tenure`, `PhoneService`, `MultipleLines`
  - `InternetService`, `OnlineSecurity`, `OnlineBackup`, `DeviceProtection`, `TechSupport`, `StreamingTV`, `StreamingMovies`
  - `Contract`, `PaperlessBilling`, `PaymentMethod`, `MonthlyCharges`, `TotalCharges`
  - `Churn` (target variable)

## Environment Setup
1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/teco-churn-analysis.git
   cd teco-churn-analysis
   ```
2. **Create and activate a Conda environment**
   ```bash
   conda create --name teco_env python=3.10
   conda activate teco_env
   ```
3. **Install dependencies**
   ```bash
   pip install -r requirement.txt
   ```

## Usage
1. **Jupyter Notebook**
   ```bash
   jupyter notebook
   ```
2. **Open** `Teco_Customer_Churn_Analysis.ipynb` and run all cells.

## Key Findings
- **Contract Type:** Month-to-month contracts have a 42% churn rate vs. 11% (1-year) and 3% (2-year).
- **Payment Method:** Electronic checks see a 45% churn rate compared to ~15–18% for other methods.
- **Tenure:** 50% churn for <1 year, dropping to 15% for >3 years.
- **Internet Service:** Fiber Optic churn at 30% vs. DSL at 20%.
- **Senior Citizens:** 41% churn vs. 26% for non-seniors.

## Recommendations
1. **Promote long-term contracts** with incentives.
2. **Encourage stable payment methods** (credit card/ACH).
3. **Implement early engagement programs** for new customers.
4. **Enhance fiber optic service quality** and guarantee speeds.
5. **Offer specialized support** for senior customers.

## Repository Structure
```
├── data/
│   └── teco_customer_data.csv
├── notebooks/
│   └── Teco_Customer_Churn_Analysis.ipynb
├── requirements.txt
└── README.md
```


