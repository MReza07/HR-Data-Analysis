## 📊 HR Data Analysis – Power BI Dashboard:

A comprehensive HR analytics project designed to help organizations make data-driven workforce decisions. This analysis focuses on employee performance, retention, demographics, absenteeism, and workforce planning. Using Power BI, the project transforms raw HR data into actionable insights that support strategic HR management.


## 📷 Dashboard Preview

![Image](https://github.com/user-attachments/assets/046179d2-f4e6-493e-83fa-f4520736300d)
![Image](https://github.com/user-attachments/assets/2c187950-e50c-4d8e-b0a5-885772851763)
![Image](https://github.com/user-attachments/assets/6056efdb-c211-44ba-8976-90051d7a6c69)
![Image](https://github.com/user-attachments/assets/13b19a49-0604-4a59-9c6b-568d82031f4b)


## 📊 Key Insights:

Attrition by Years with Current Manager: ​

Attrition is highest for employees with 0-2 years with their current manager.

Attrition is highest for Research & Development

## 🛠️ Tools & Technologies

Power BI Desktop (Version: 2024) – Dashboard development, modeling, DAX calculations

Excel 2021 / CSV – Data cleaning and preparation

Power Query – Data transformation

DAX Measures – KPI creation and analytical modeling

## 📁 Project Structure:

HR Data Analysis

│── Data/

│     └── HR_Dataset.csv
│── Report/

│     └── HR_Analytics_Dashboard.pbix

├── 📄 Screenshot/

│   ├── HR Data analysis_Employee Attrition.JPG

│   ├── HR Data analysis_Salary & Career Analysis.JPG

│   ├── HR Data analysis_Satisfaction & Job Insights.JPG

│   ├── HR Data analysis_Workforce Demographics.JPG

│── README.md

## 📈 Dashboard Features

Interactive filters for department, gender, experience level, and job role

Drill-down capability for detailed employee-level analysis

KPIs such as:

Total Employees

Active Employees

Attrition Rate

Average Age

Average Salary

Job Satisfaction Score

## 🧮 Sample DAX Measures:

Attrition Rate = 

DIVIDE(
    CALCULATE(COUNT('Employees'[EmployeeID]), 'Employees'[Attrition] = "Yes"),
    COUNT('Employees'[EmployeeID])
)

Average Salary = AVERAGE('Employees'[MonthlyIncome])


Total Employees = COUNTROWS(HR_Analytics)

Active Employees = [Total Employees]-[Attrition]


Attrition = CALCULATE(COUNTROWS(HR_Analytics),HR_Analytics[Attrition]="Yes")

## ✨ Key Outcomes

Identified major attrition drivers such as job role, overtime, and salary band

Highlighted departments with low performance scores and high absenteeism

Revealed demographic patterns supporting better workforce planning

Delivered insights to improve employee engagement and retention strategies

## How to Use

1. Clone the repository://github.com/MReza07/HR-Data-Analysis.git

2.Install Power BI Desktop://www.microsoft.com/en-us/power-platform/products/power-bi/desktop

3. Open the file
 
   `HR_Analytics.pbix` in Power BI Desktop.

5. Go to Home → Transform Data → Refresh to load latest dataset.

6. Navigate between pages using left panel in Power BI.

8. Explore and analyze the data using the interactive dashboards.
   


## 📜 License

This project is distributed under the MIT License.

## 📬 Contact

Feel free to reach out for collaboration, dashboard customization, or HR analytics assistance.

📧 Email:reazulrepon@gmail.com

💼 GitHub:https://github.com/MReza07




