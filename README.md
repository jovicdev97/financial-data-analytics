# Loan Dataset Analysis with Python

## Overview
This project analyzes a synthetic loan dataset using Python, focusing on data manipulation with Pandas and NumPy, and visualization using Matplotlib and Seaborn. The analysis explores various aspects of loan applications including credit scores, income levels, employment status, and interest rates.

## Dataset
The dataset (`Loan.csv`) is a synthetic dataset created to mimic real-world loan application data. Using synthetic data ensures privacy and ethical compliance while still providing realistic patterns for analysis.

### Source
- Dataset: Synthetic Loan Dataset
- Platform: Kaggle
- Link: [financial-risk-for-loan-approval](https://www.kaggle.com/datasets/lorenzozoppelletto/financial-risk-for-loan-approval)
- Type: Synthetic/Generated Data
- Records: 20,000
- Features: 36 columns

### Why Synthetic Data?
Using synthetic data is crucial for:
- Protecting individual privacy
- Avoiding ethical concerns related to financial data
- Allowing open sharing and collaboration
- Maintaining realistic data patterns while eliminating sensitive information

### Dataset Features
- Application details (date, loan amount, duration)
- Personal information (age, employment status, education)
- Financial metrics (annual income, credit score, interest rates)
- Risk assessment (risk score, loan approval status)

## Analysis Features

### 1. Data Loading and Initial Exploration
- Loading dataset using Pandas
- Basic data examination with head() function
- Data cleaning and preprocessing

### 2. Array Operations with NumPy
- Creating and manipulating different data type arrays
- Filtering operations
- Statistical calculations

### 3. Financial Analysis
- Debt-to-Income ratio calculations
- Monthly payment analysis
- Interest rate examination
- Credit risk assessment

### 4. Data Visualization
- Line chart: Interest rates over time
- Bar chart: Distribution of employment status
- Histogram: Annual income distribution
- Box plot: Interest rates by education level
- Scatter plot: Credit score vs interest rate correlation

## Key Insights
- Interest rates remain relatively stable over the analyzed time period
- Most loan applicants are employed
- Majority of applicants have annual income under $100,000
- Higher credit scores correlate with lower interest rates
- Education level shows minimal impact on base interest rates

## Technical Requirements
### Dependencies
- Python 3.x
- NumPy >= 1.19.2
- Pandas >= 1.2.0
- Matplotlib >= 3.3.2
- optional: (Seaborn >= 0.11.0)

### Hardware Requirements
- Minimum 4GB RAM
- 1GB free disk space

## Installation
```bash
# Create virtual environment (optional but strongly (!) recommended)
python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate

# Install required packages
pip install numpy pandas matplotlib seaborn

# Clone repository
git clone https://github.com/jovicdev97/loan-analysis.git
cd loan-analysis
Usage
Clone this repository
Place the Loan.csv dataset in the project directory
Run the Jupyter notebook:
bash

Kopieren
jupyter notebook loan_analysis.ipynb
Project Structure
basic

Kopieren
loan-analysis/
│
├── data/
│   └── Loan.csv
│
├── notebooks/
│   └── loan_analysis.ipynb
│
├── README.md
└── requirements.txt

# Source
Kaggle https://www.kaggle.com/datasets/lorenzozoppelletto/financial-risk-for-loan-approval
