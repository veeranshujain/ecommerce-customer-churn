# E-Commerce Customer Churn Prediction

This is a data science project where I explore e-commerce sales data to understand customer buying behavior and identify customers who may stop purchasing.

### What I did
- Cleaned and explored the transaction data using Python.
- Analyzed customer purchases, spending, and buying frequency.
- Created customer-level features for churn analysis.
- Trained and compared Logistic Regression and Random Forest models.
- Evaluated model performance and explored customer risk scores.

### Tools Used
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Jupyter Notebook.

### Results
Logistic Regression performed better than Random Forest in my current evaluation, with a ROC-AUC score of **0.688**.

### Dataset
[UCI Online Retail Dataset](https://archive.ics.uci.edu/dataset/352/online+retail)

**Note:** The dataset doesn't contain an actual churn label, so I used future purchase inactivity as a proxy. This is a learning project, and the results need further validation.
