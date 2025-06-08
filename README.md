
# 💼 Salaries Dashboard

This project delivers an interactive **Power BI dashboard** and **exploratory data analysis (EDA)** to uncover patterns in employee salaries. By using **Excel**, **Python**, **Power BI**, and **DAX**, the project identifies trends in compensation based on job titles, highlights top earners by name and role, and compares total pay with benefits and other components.

## 🎯 Project Objective

To analyze employee salary data and extract actionable insights related to:

- Salary distribution by **job title**  
- Identification of **top earning employees** by name and title  
- Comparison between **total pay** and **pay with benefits**  
- Yearly trends in **overtime pay**, **other pay**, and **benefits**  
- Relationship between salary components across different roles  

## 🛠️ Tools & Technologies

| Tool        | Purpose                                        |
|-------------|------------------------------------------------|
| Excel       | Initial data formatting and inspection         |
| Python (`pandas`, `numpy`) | Data cleaning and preprocessing          |
| Power BI    | Dashboard design and visual storytelling       |
| DAX         | Custom measures, KPIs, and financial metrics   |

## 🧪 Data Cleaning & Challenges

During preprocessing, several data issues were resolved:
- **Missing values**: Filled or handled null entries in salary and job fields
- **Duplicates**: Removed repeated records to avoid bias
- **Formatting**: Standardized job titles, pay formats, and numeric types

## 📊 Exploratory Data Analysis

Python was used to summarize salary trends, find top earners, and analyze job title frequency:

```python
import pandas as pd
import numpy as np
```

## 📈 Power BI Dashboard

The Power BI report includes four pages:

1. **Home** – Overview KPIs and summary visuals  
2. **Job Title Details** – Breakdown of pay by role  
3. **Employee Details** – Insights by employee and benefits  
4. **Table** – Raw data view and filters  

### 📌 DAX Measures Used

Some custom DAX measures used in the dashboard:

- `Adjusted TotalPay`  
- `AVG Total Pay`  
- `AVG Total Pay With Benefits`  
- `Gif one`  
- `Top_20_Employees`  
- `Top_20_Salaries`  
- `Total Pay`  
- `Total Pay With Benefits`  
- `TotalPay_Display`  
- `TotalPay_Formatted`  
- `TotalSales`  
- `TtttotalPay_Formatteed`  

## 📊 Key Visualizations

- **Average Total Pay With Benefits**
- **Average Total Pay by Job Title**
- **Overtime Pay by Year**
- **Other Pay by Year**
- **Job Title by Total Pay**
- **Average of Benefits**
- **Total Pay With Benefits by Year**
- **Total Pay by Year**
- **AVG Pay and Benefits by Employee Name**
- **Base Pay by Employee**
- **Comparison: Benefits, Other Pay, and Overtime Pay**
- **Comparison: Total Pay vs Total Pay With Benefits**
- **Employee Count by Year**
- **Raw Table View**

## 📂 Folder Structure

```
salaries-dashboard/
├── data/                  # Raw and cleaned datasets
├── python-analysis/       # Scripts and data exploration notebooks
├── dashboard/             # Power BI (.pbix) file
├── visuals/               # Dashboard screenshots
└── README.md              # Project documentation
```

## 🔍 Dataset

Employee salary dataset (Base Pay, Total Pay, Job Titles, Benefits, etc.). Cleaned and formatted before visualization.

## 📬 Author

**Mahmoud Mohamed Fawzy Elzayat**  
[🔗 LinkedIn](https://www.linkedin.com/in/mahmoud-elzayat-data-analysis)

## License

This project is licensed under the **Creative Commons BY-NC-ND 4.0**.  
You may not use this project for commercial purposes or modify it.  
[View full license](https://creativecommons.org/licenses/by-nc-nd/4.0/)
