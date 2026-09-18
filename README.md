# Customer Churn Analysis

A data analysis project that explores customer churn patterns using the Telco Customer Churn dataset.

## Project Overview

This project cleans, explores, and visualizes customer data to identify factors associated with customer churn. The analysis examines contract type, tenure, monthly charges, internet service, payment method, senior-citizen status, and gender.

## Key Findings

- Overall customer churn rate: approximately **26.58%**
- Month-to-month customers had a churn rate of approximately **42.71%**
- Customers with 0–12 months of tenure had the highest churn rate, approximately **47.68%**
- Customers with 61–72 months of tenure had a much lower churn rate, approximately **6.61%**
- Fiber optic customers had a churn rate of approximately **41.89%**
- Electronic check users had a churn rate of approximately **45.29%**
- Senior citizens had a higher churn rate than non-senior customers
- Churn rates were similar across genders

## Tools Used

- Python
- Jupyter Notebook
- Pandas
- Matplotlib

## Project Structure

```text
customer-churn-analysis/
│
├── Customer_Churn_Analysis.ipynb
└── README.md
```

## How to Run

1. Clone this repository.
2. Open `Customer_Churn_Analysis.ipynb` in Jupyter Notebook or JupyterLab.
3. Install the required Python libraries if needed:

```bash
pip install pandas matplotlib
```

4. Run the notebook cells in order.

## Dataset

The analysis uses the Telco Customer Churn dataset, containing customer demographics, account information, subscribed services, and churn status.

## Conclusion

The analysis shows that churn is strongly associated with short tenure, month-to-month contracts, fiber optic service, electronic-check payments, and higher monthly charges. These findings can help businesses identify customer groups that may benefit from retention efforts.

> Note: The results describe patterns in this dataset and do not prove causation.
