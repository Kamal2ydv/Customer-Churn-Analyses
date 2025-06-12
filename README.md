# Customer Churn Analysis

This project focuses on analyzing customer churn data to understand the key factors influencing why customers leave a telecom company. The dataset includes information on customer demographics, tenure, service usage, and payment methods.

## 📊 Objective

The main goal is to:

- Identify patterns and reasons for customer churn.
- Provide insights to help the company reduce future churn.
- Visualize relationships between churn and key customer attributes.

## 🧹 Data Preprocessing

- **Blank Fields Handling**: Missing values in the `TotalCharges` column were replaced with 0 where tenure was also 0.
- **Categorical Conversion**: Senior citizen data was converted from 0/1 to `Yes`/`No` for clarity.

## 🔍 Key Insights

- 📉 **Churn Rate**: About **26.54%** of customers have churned.
- 👵 **Senior Citizens**: A higher proportion of senior citizens have churned compared to younger customers.
- ⏳ **Tenure Impact**: Customers who stayed only 1–2 months were more likely to churn, while long-term users showed more loyalty.
- 🧾 **Billing Preferences**: Monthly billing was more associated with churn compared to long-term contracts.

## 📈 Visual Analysis

The analysis uses various visualizations to uncover patterns:
- Pie charts for churn distribution
- Bar graphs comparing churn across different categories like `Contract`, `PaymentMethod`, and `Tenure`
- Count plots to explore categorical feature impacts

## 🛠 Tools Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook

## 🚀 How to Run

1. Clone this repository.
2. Open the `.ipynb` file in Jupyter Notebook or VSCode.
3. Run the cells step-by-step to reproduce the analysis.

```bash
git clone https://github.com/your-username/customer-churn-analysis.git
