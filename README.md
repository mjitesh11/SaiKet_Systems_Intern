# 🎯 Internship Project: Customer Segmentation Visualization & Advanced Analysis

## 📌 Project Title:*Customer Segmentation Visualization & Advanced Analysis*

## 🎯 Objectives

The main objectives of this project are:

- Analyze customer churn behavior in a telecom dataset.
- Perform customer segmentation based on tenure and services.
- Develop visual dashboards and reports for identifying churn patterns.
- Provide actionable insights to reduce customer churn and improve retention.
- Support data-driven decisions using advanced analysis and statistics.

## 🧱 Project Structure

```plaintext
📁 customer-churn-analysis/
│
├── 📊 customer_churn_analysis.ipynb     # Main Jupyter Notebook for analysis
├── 📄 README.md                         # Project documentation
├── 📦 requirements.txt                  # Dependencies
├── 📁 data/
│   └── Telco_Customer_Churn_Dataset.csv  # Source dataset
├── 📁 output/
│   └── cleaned_data.csv                 # Cleaned dataset (after processing)
│   └── visualizations/                  # Generated charts & plots
└── 📁 models/                           # Future scope: Predictive models


---

🛠 Technologies Used

Python (v3.7+)

Pandas – data manipulation

NumPy – numerical computation

Matplotlib – visualizations

Seaborn – statistical plots

Plotly – interactive charts (donut, bar, etc.)

Jupyter Notebook – code and results integration



---

📈 Dataset Overview

Dataset: Telco_Customer_Churn_Dataset.csv
Rows: ~7,000
Columns: 21

Main Attributes:

customerID, gender, SeniorCitizen, Partner, Dependents

tenure, PhoneService, InternetService, Contract, PaymentMethod

MonthlyCharges, TotalCharges, Churn



---

🔍 Data Preview

customerID	gender	tenure	MonthlyCharges	TotalCharges	Churn

7590-VHVEG	Female	1	29.85	29.85	No
5575-GNVDE	Male	34	56.95	1889.5	No
...	...	...	...	...	...



---

🧪 Installation & Setup

> 🖥 Requirements: Python 3.7 or higher



🔧 Step-by-step Setup

1. Clone the repository:



git clone https://github.com/yourusername/customer-churn-analysis.git
cd customer-churn-analysis

2. Install required libraries:



pip install -r requirements.txt

3. Open Jupyter Notebook:



jupyter notebook

4. Run customer_churn_analysis.ipynb step by step




---

📊 Tasks Overview

✅ Task 1: Understand the Dataset

Load dataset, view first 10 rows, check data types, and missing values.


✅ Task 2: Data Cleaning

Handle missing values (impute/drop), remove duplicates, and standardize column names.


✅ Task 3: Exploratory Data Analysis (EDA)

Summary statistics (mean, median, mode)

Histograms and boxplots for numerical columns

Churn rate analysis


✅ Task 4: Customer Segmentation Visualization

Tenure distribution: pie/donut charts (0–12, 13–36, 37+ months)

Clustered bar charts of average monthly charges by tenure group


✅ Task 5: Advanced Analysis

Group by tenure and compute churn rate and charges

Analyze churn by demographics and contract types

Compare payment methods



---

📌 Insights & Outcomes

Majority of churners are on month-to-month contracts.

Customers with higher tenure tend to stay.

Senior citizens and customers with electronic check payment method are more likely to churn.



---

🚀 Future Improvements

Add machine learning models to predict churn.

Deploy as a dashboard using Streamlit or Dash.

Perform cohort and lifecycle analysis.



---

📬 Contact

Author: Majji Jitesh
Email: majjijtesh11@gmail.com
GitHub: mjitesh11
