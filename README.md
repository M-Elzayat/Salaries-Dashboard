💼 Salaries Dashboard
This project delivers an interactive Power BI dashboard and exploratory data analysis (EDA) to uncover patterns in employee salaries. By using Excel, Python, Power BI, and DAX, the project identifies trends in compensation based on job titles, highlights top earners by name and role, and compares total pay with benefits and other components.

🎯 Project Objective
To analyze employee salary data and extract actionable insights related to:

Salary distribution by job title

Identification of top earning employees by name and title

Comparison between total pay and pay with benefits

Yearly trends in overtime pay, other pay, and benefits

Relationship between salary components across different roles

🛠️ Tools & Technologies
Tool	Purpose
Excel	Initial data formatting and inspection
Python (pandas, numpy)	Data cleaning and preprocessing
Power BI	Dashboard design and visual storytelling
DAX	Custom measures, KPIs, and financial metrics

🧪 Data Cleaning & Challenges
During preprocessing, several data issues were resolved:

Missing values: Filled or handled null entries in salary and job fields

Duplicates: Removed repeated records to avoid bias

Formatting: Standardized job titles, pay formats, and numeric types

📈 Exploratory Data Analysis (Python)
Python was used (mainly with pandas and numpy) for:

Summarizing average and total pay

Identifying high-salary employees

Analyzing job title frequency and pay distribution

📊 Power BI Dashboard
The Power BI report includes 3 main pages:

Home – Overview KPIs, summary visuals, key trends

Job Title Details – Pay breakdown by job roles, comparison visuals

Employee Details – Top earners by name, base pay, and benefits

Table – Raw data table with filters

📌 DAX Measures Used
Custom measures were built using DAX to enable dynamic analysis:

Adjusted TotalPay

AVG Total Pay

AVG Total Pay With Benefits

Gif one

Top_20_Employees

Top_20_Salaries

Total Pay

Total Pay With Benefits

TotalPay_Display

TotalPay_Formatted

TotalSales

TtttotalPay_Formatteed

📊 Key Visualizations
Some of the core visuals and analytical comparisons created include:

Average Total Pay by Job Title

Total Pay With Benefits by Year

Other Pay & Overtime Pay by Year

Job Title by Total Pay

Comparison: Total Pay vs Total Pay With Benefits

Average Benefits by Employee Name

Base Pay by Employee

Count of Employees by Year

Breakdown: Benefits, Overtime Pay, Other Pay

📂 Folder Structure
salaries-dashboard/
├── data/                  # Raw and cleaned datasets
├── python-analysis/       # Scripts and data exploration notebooks
├── dashboard/             # Power BI (.pbix) file
└── README.md              # Project documentation
🔍 Dataset
The dataset includes employee salary information (base pay, total pay, benefits, etc.) and job titles. Data was cleaned and standardized before dashboard development.

## 📬 Author

**Mahmoud Mohamed Fawzy Elzayat**  
[🔗 LinkedIn](https://www.linkedin.com/in/mahmoud-elzayat-data-analysis)
