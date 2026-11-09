# Customer Churn Analysis

## Project Overview

This project explores customer churn in a telecommunications company using Python and exploratory data analysis (EDA).

The goal is to understand customer behaviour, identify patterns associated with churn, and uncover insights that could help a business improve customer retention.

## Business Problem

Customer churn occurs when customers stop using a company's services. High churn can reduce revenue and increase the cost of acquiring new customers.

This project investigates:

- What proportion of customers leave the company?
- Are some customer groups more likely to churn?
- How are monthly charges and total charges related to churn?
- What patterns could help the business improve customer retention?

## Dataset

The project uses the **IBM Telco Customer Churn dataset**, which contains information about 7,043 customers.

It includes information about:

- Customer demographics
- Services and subscriptions
- Contract types
- Monthly and total charges
- Customer tenure
- Churn status

## Tools and Technologies

- **Python** – data analysis
- **Pandas** – data manipulation and cleaning
- **NumPy** – numerical operations
- **Matplotlib** – data visualization
- **Seaborn** – statistical visualization
- **Jupyter Notebook** – interactive analysis

## Project Workflow

1. Loaded and explored the customer dataset.
2. Checked data types and missing values.
3. Cleaned the data, including converting `TotalCharges` to numeric values.
4. Checked for duplicate records.
5. Analysed customer churn distribution.
6. Explored customer demographics and billing patterns.
7. Created visualizations to identify trends and relationships.
8. Saved the cleaned dataset for future analysis.

## Key Findings

- The dataset contains **7,043 customer records**.
- Overall customer churn is approximately **26.54%**.
- Approximately **73.46%** of customers remained with the company.
- There were 11 missing values in `TotalCharges`. These belonged to customers with zero months of tenure and were filled with zero.
- No duplicate records were found.

## Business Recommendation

The churn rate suggests that customer retention is an important business challenge.

Further analysis of contract types, tenure, service subscriptions, and monthly charges could help identify customers at higher risk of leaving.

The business could use these insights to develop targeted customer retention strategies.

## Project Structure

```text
customer-churn-analysis/
│
├── customer_data_analysis.ipynb
│
├── data/
│   ├── raw/
│   │   └── Telco-Customer-Churn.csv
│   │
│   └── processed/
│       └── cleaned_customer_churn.csv
│
├── .gitignore
│
└── README.md
```

## How to Run This Project

1. Clone this repository:

```bash
git clone https://github.com/BhowanKhawas/customer-churn-analysis.git
```

2. Navigate into the project folder:

```bash
cd customer-churn-analysis
```

3. Install the required libraries:

```bash
python -m pip install pandas numpy matplotlib seaborn jupyter
```

4. Start Jupyter Notebook:

```bash
jupyter notebook
```

5. Open `customer_data_analysis.ipynb` and run the notebook cells.

## Future Improvements

- Perform deeper analysis of factors associated with customer churn.
- Write SQL queries to analyse customer behaviour.
- Build an interactive dashboard using Power BI.
- Develop a machine learning model to predict customer churn.
- Build and deploy an interactive churn prediction application.

## Author

**Bhowan Khawas**

GitHub: [BhowanKhawas](https://github.com/BhowanKhawas)

---

*This project is part of my journey towards building practical data analytics and data science skills.*
