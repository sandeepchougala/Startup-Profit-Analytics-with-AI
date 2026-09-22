# Startup Profit Prediction & Business Analytics with AI

Data Analytics with AI project submitted as part of the **IBM SkillsBuild Data
Analytics with AI Academic Internship Program**, conducted by BharatCares in
association with AICTE.

## Project Description

This project analyzes financial data of 50 startups — their R&D spend,
administration spend, marketing spend, and state of operation — to
understand which factors most strongly drive profit. The goals are to:

1. Perform exploratory data analysis (EDA) to understand how spending
   categories and location relate to profit.
2. Train regression models (Linear Regression and Random Forest) to
   predict a startup's profit from its spending pattern.
3. Translate the findings into business/investment recommendations.

## Dataset

- **Name:** 50 Startups
- **Rows:** 50
- **Columns:** `R&D Spend`, `Administration`, `Marketing Spend`, `State`,
  `Profit`

## Technologies Used

- Python 3
- pandas, numpy — data manipulation
- matplotlib, seaborn — data visualization
- scikit-learn — Linear Regression, Random Forest Regressor
- Jupyter Notebook

## Project Structure

```
├── Sandeep_StartupProfitAnalytics.ipynb   # Main analysis notebook
├── 50_Startups.csv                        # Dataset
├── requirements.txt                       # Python dependencies
└── README.md                              # This file
```

## Setup / Run Instructions

1. Clone this repository:
   ```bash
   git clone <your-repo-url>
   cd <repo-folder>
   ```
2. (Optional) Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate   # Windows: venv\Scripts\activate
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Launch the notebook:
   ```bash
   jupyter notebook Sandeep_StartupProfitAnalytics.ipynb
   ```
5. Run all cells (Cell → Run All).

## Key Findings

- **R&D Spend** is the strongest driver of profit among all features.
- **Marketing Spend** has a moderate positive relationship with profit.
- **Administration Spend** shows little to no relationship with profit.
- **State/location** has only a minor effect on profit compared to
  spending pattern.
- A Random Forest Regressor achieved an **R² score of ~0.92** predicting
  profit on the held-out test set, slightly outperforming Linear
  Regression (R² ~0.90).

## Recommendations

1. Prioritize R&D investment over other spending categories.
2. Maintain moderate marketing spend for steady returns.
3. Review and potentially trim administration costs.
4. Do not over-weight location when evaluating investment potential.

## Author

Sandeep Shrishail Chougala — BCA student, IBM SkillsBuild Data Analytics
with AI Academic Internship (BharatCares x AICTE), 2026.
