# Zenvy Payroll SaaS – Week 1: Data Science Analysis

## 📌 Project Overview
This repository contains the Week 1 deliverables for the **Zenvy Payroll SaaS** Data Science Internship. The primary focus of this week was establishing a foundation in the payroll domain, researching SaaS architecture, and performing Exploratory Data Analysis (EDA) on a large-scale payroll dataset.

## 📂 Repository Contents
* `Zenvy Week 1 Plan Uzma Patel - Data Science.ipynb`: The primary Jupyter Notebook containing data cleaning, metric calculation, and visualizations.
* `Payroll Data.csv`: The raw dataset used for analysis (685,401 records).

## 🛠️ Tech Stack
- **Language:** Python 3.x
- **Libraries:** - `Pandas`: Data wrangling and cleaning.
    - `NumPy`: Numerical computation.
    - `Matplotlib` & `Seaborn`: Statistical data visualization.

## 🔍 Week 1 Analysis Highlights

### 1. Domain Knowledge & Research
- **Payroll Basics:** Studied salary components (Basic, HRA, Allowances), deductions (Tax, PF), and the impact of overtime and leaves on net payout.
- **Competitor Study:** Analyzed market leaders like **Zoho Payroll**, **GreytHR**, and **Keka** to understand standard dashboard features.
- **SaaS Architecture:** Explored multi-tenant cloud structures, backend business logic (Python/Java), and secure client access protocols.

### 2. Data Cleaning Pipeline
As identified in the notebook, the following pre-processing steps were taken:
- **Header Sanitization:** Removed trailing spaces from column names to ensure code stability.
- **Dtype Handling:** Resolved mixed-type warnings by converting salary columns from strings/objects to numeric floats.
- **Missing Value Management:** Identified and labeled null values in critical fields like `Departments` and `Employee Status`.

### 3. Key Metrics for SaaS Dashboard
The notebook calculates the following essential KPIs:
- **Average Basic Salary per Department:** Identifying pay scales across Business Units.
- **Total Employee Cost (CTC):** Summing `Basic Salary` + `Allowance` + `Statutory Bonus`.
- **Payroll Composition:** Visualizing the ratio of base pay versus variable allowances.

## 📊 Visualizations Included
1. **Average Salary Distribution:** A categorical bar chart showing salary trends by department.
2. **Total Cost Breakdown:** A stacked bar chart illustrating the contribution of bonuses and allowances to the total departmental expenditure.



## 🚀 How to Run the Notebook
1. Clone this repository or download the files.
2. Ensure you have the dependencies installed:
   ```bash
   pip install pandas numpy matplotlib seaborn
