HR Data Analysis – Power BI Dashboard:

A comprehensive HR analytics project designed to help organizations make data-driven workforce decisions. This analysis focuses on employee performance, retention, demographics, absenteeism, and workforce planning. Using Power BI, the project transforms raw HR data into actionable insights that support strategic HR management.


📷 Dashboard Preview
![Image](https://github.com/user-attachments/assets/046179d2-f4e6-493e-83fa-f4520736300d)
![Image](https://github.com/user-attachments/assets/2c187950-e50c-4d8e-b0a5-885772851763)
![Image](https://github.com/user-attachments/assets/6056efdb-c211-44ba-8976-90051d7a6c69)
![Image](https://github.com/user-attachments/assets/13b19a49-0604-4a59-9c6b-568d82031f4b)


📊 Key Insights Covered:
Overview

Total Employees: 1480 ​
Active Employees: 1242 ​
Attrition Count: 238 ​
Attrition Rate: 16% ​
Average Age: 36.92 years ​
Average Monthly Income: $6,500 ​
Average Job Satisfaction: 2.73 ​


Attrition Analysis


By Department: ​

Research & Development: 151 (63.45%) ​
Sales: 87 (36.55%) ​
Human Resources: 0 (0%) ​



By Age Group: ​

18-25: 12
26-35: 44
36-45: 43
46-55: 27
55+: 8



By Gender:

Male: 151 (63.45%) ​
Female: 87 (36.55%) ​



By Overtime:

Yes: 128
No: 110



By Business Travel:

Non-Travel: 69
Travel_Rarely: 128
Travel_Frequently: 41



By Education Field: ​

Life Sciences: 89 ​
Medical: 63 ​
Marketing: 36 ​
Technical Degree: 32 ​
Other: 11 ​
Human Resources: 7 ​



By Distance from Home:
Attrition is distributed across various distances, with peaks at shorter distances. ​



Employee Distribution


By Age Group: ​

26-35: 611 employees ​
36-45: 328 employees
46-55: 228 employees ​
18-25: 123 employees ​
55+: 47 employees ​



By Gender:

Male: 889 employees ​
Female: 591 employees



By Marital Status: ​

Married: 679 employees ​
Single: 473 employees
Divorced: 328 employees ​



By Department: ​

Research & Development: 967 employees ​
Sales: 450 employees ​
Human Resources: 63 employees ​



By Job Role:

Sales Executive: 329 employees ​
Research Scientist: 293 employees
Laboratory Technician: 261 employees
Manufacturing Director: 147 employees
Healthcare Representative: 132 employees
Manager: 102 employees ​
Sales Representative: 84 employees
Research Director: 80 employees ​
Human Resources: 52 employees ​



By Job Level:

Level 1: 545 employees ​
Level 2: 539 employees ​
Level 3: 220 employees ​
Level 4: 107 employees ​
Level 5: 69 employees



By Work-Life Balance:

Level 1: 81 employees ​
Level 2: 346 employees ​
Level 3: 899 employees ​
Level 4: 154 employees ​



By Stock Option Level:

Level 0: 636 employees ​
Level 1: 601 employees ​
Level 2: 158 employees ​
Level 3: 85 employees ​




Training and Income


Average Training Times Last Year by Job Role: ​

Sales Representative: 3.00 ​
Laboratory Technician: 2.95 ​
Sales Executive: 2.83 ​
Manager: 2.81 ​
Research Director: 2.78 ​
Healthcare Representative: 2.77 ​
Manufacturing Director: 2.72 ​
Research Scientist: 2.67 ​
Human Resources: 2.56 ​



Average Monthly Income by Job Role: ​

Research Director: $17.2K
Manager: $15K
Healthcare Representative: $10K
Manufacturing Director: $7.5K
Sales Executive: $7.3K
Human Resources: $6.9K
Research Scientist: $4.2K
Laboratory Technician: $3.2K
Sales Representative: $2.6K




Additional Insights


Attrition by Years with Current Manager: ​
Attrition is highest for employees with 0-2 years with their current manager.

🛠️ Tools & Technologies

Power BI – Dashboard development, modeling, DAX calculations

Excel / CSV – Data cleaning and preparation

Power Query – Data transformation

DAX Measures – KPI creation and analytical modeling

📁 Project Structure:

│── Data/
│     └── HR_Dataset.csv
│── PBIX/
│     └── HR_Analytics_Dashboard.pbix
│── Images/
│     └── HR_Dashboard_Screenshot.png
│── README.md

📈 Dashboard Features

Interactive filters for department, gender, experience level, and job role

Drill-down capability for detailed employee-level analysis

KPIs such as:

Total Employees

Active Employees

Attrition Rate

Average Age

Average Salary

Job Satisfaction Score

🧮 Sample DAX Measures:

Attrition Rate = 
DIVIDE(
    CALCULATE(COUNT('Employees'[EmployeeID]), 'Employees'[Attrition] = "Yes"),
    COUNT('Employees'[EmployeeID])
)


Average Salary = AVERAGE('Employees'[MonthlyIncome])


✨ Key Outcomes

Identified major attrition drivers such as job role, overtime, and salary band

Highlighted departments with low performance scores and high absenteeism

Revealed demographic patterns supporting better workforce planning

Delivered insights to improve employee engagement and retention strategies

How to Use
1. Clone the repository: git clone https:[//github.com/mayourbukhari/Data-Analytics-Projects-with-Power-BI.git](https://github.com/MReza07/HR-Data-Analysis/tree/main/Report)
2. 
3. Install Power BI Desktop: Download Link-https://www.microsoft.com/en-us/power-platform/products/power-bi/desktop
4. 
5. Open the project file in Power BI Desktop.

6. Basic Power BI Knowledge: Familiarity with Power BI Desktop, including data import, DAX calculations, and dashboard creation.

8. Explore and analyze the data using the interactive dashboards.

📬 Contact

Feel free to reach out for collaboration, dashboard customization, or HR analytics assistance.

📧 Email:reazulrepon@gmail.com

💼 GitHub profile link-https://github.com/MReza07




