# Price-Demand-Sensitivity-Analysis

This project focuses on analyzing how price influences consumer demand using real-world retail scanner data. The goal is to measure Price Elasticity of Demand (PED), study demand patterns, and generate insights for optimal pricing decisions grounded in microeconomic theory.

# About the Project

Objective

The aim of this project is to quantify how changes in price affect quantity demanded and revenue. The analysis includes exploring retail sales behavior, identifying demand patterns, estimating elasticity, and understanding how pricing decisions impact revenue.

Dataset

This project uses retail [scanner data](https://www.kaggle.com/datasets/marian447/retail-store-sales-transactions), which typically contains:

- Date of Sales Transaction
- Customer ID
- Transaction ID
- SKU Category ID
- SKU ID
- Quantity Sold
- Sales Amount (Unit price times quantity. For unit price, please divide Sales Amount by Quantity.)

The dataset enables a full price–quantity–revenue analysis essential for elasticity calculations.

# Features

✔ Data Cleaning

- Removed missing or invalid entries
- Converted price/quantity/revenue columns to numeric format
- Created standardized metrics for demand analysis
- Filtered out anomalies and extreme outliers

✔ Exploratory Data Analysis (EDA)

- Distribution of price and quantity
- Demand curve (Price vs Quantity)
- Revenue behavior across price levels
- Category-wise price insights (if available)
- Summary statistics for key economic variables

✔ Price Elasticity of Demand (PED)

- Log–log regression using Statsmodels
- Computed elasticity coefficient
- Identified elastic vs inelastic products
- Interpreted elasticity in economic context
- Connected insights to revenue maximization theory

✔ Visual Insights

- Price distribution histogram
- Quantity distribution histogram
- Scatter plot for demand curve
- Price vs revenue curve
- Regression line (log–log) for elasticity interpretation

# Demo (Sample Visuals)

Price vs Quantity (Demand Curve)

<img width="621" height="473" alt="output" src="https://github.com/user-attachments/assets/05495430-b8ed-4975-84e6-d9d1261070d4" />

Price vs Revenue
(Shows revenue peaks and decline at higher prices)

<img width="621" height="473" alt="output111" src="https://github.com/user-attachments/assets/493b0df9-3cc8-4965-9164-dab2182d47bf" />

# Dependencies Used

- `NumPy` — numerical operations
- `Pandas` — dataset cleaning + manipulation
- `Matplotlib & Seaborn` — visualizations
- `Statsmodels` — log–log regression for elasticity estimation

# How to Run the Project

Follow these steps to run the Retail Price Elasticity Analysis project on your local machine.

1️⃣ Clone the Repository
```
git clone <your-repository-link>
```
Navigate to the project directory:
```
cd <your-project-folder>
```

2️⃣ Set Up a Virtual Environment
```
python -m venv venv
```
Activate it:
Windows
```
venv\Scripts\activate
```
macOS/Linux
```
source venv/bin/activate
```

Install dependencies:
```
pip install numpy pandas matplotlib seaborn statsmodels
```

3️⃣ Load the Dataset

Place your CSV file inside a folder named:
```
data/
    scanner_data.csv
```

4️⃣ Open the Notebook

Launch Jupyter Notebook:
```
jupyter notebook
```
Then open:
```
Retail_Price_Elasticity_Analysis.ipynb
```

5️⃣ Run All Cells

Inside Jupyter:
- Click Run All, or
- Use Shift + Enter to execute cells sequentially

6️⃣ You're Done! 🎉

You can now explore:
- Demand curves
- Price–quantity relationships
- Elasticity coefficients
- Revenue optimization insights

# File Details

- `Retail_Price_Elasticity_Analysis.ipynb` — Full analysis notebook (cleaning → EDA → elasticity).
- `scanner_data.csv` — Raw retail data used in the project.
- `README.md` — Documentation explaining purpose and steps.
- `elasticity_summary.pdf` — Structured PDF summarizing results and key insights.


<p align="center"> <strong> Built by Sandeep Mehta </strong> </p> <p align="center"> <a href="https://github.com/sandeepmehta08"> <img src="https://img.shields.io/badge/GitHub-sandeepmehta08-black?logo=github&style=for-the-badge"/> </a> <a href="https://www.linkedin.com/in/sandeep-mehta-25bb99231/"> <img src="https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin&style=for-the-badge"/> </a> </p>








