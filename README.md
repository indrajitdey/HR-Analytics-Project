# HR Analytics Dashboard - Employee Attrition Prediction
![Screenshot 2024-10-16 171516](https://github.com/user-attachments/assets/28ddea4a-292c-43e2-813a-38e53763b9f7)

## Problem Statement
Employee attrition is a significant concern for organizations, especially when the cost of replacing and training new employees is high. Predicting which employees are likely to leave the company helps in proactive decision-making and retention strategies. The goal of this project is to analyze employee data and predict factors contributing to attrition, allowing businesses to develop targeted interventions to reduce turnover.

## Data Overview
The dataset contains comprehensive employee information, including demographic details, job-related factors, and performance metrics. The key variables include:
- EmpID: Unique identifier for each employee
- Age: Employee's age
- AgeGroup: Categorized age ranges (e.g., 18-25, 26-35)
- Attrition: Whether the employee has left the company (Yes/No)
- Department: Department of the employee (e.g., Research & Development, Sales)
- JobRole: Specific job title within the department
- MaritalStatus: Employee's marital status
- Gender: Employee's gender
- Education: Education level (numeric)
- EducationField: Field of study (e.g., Life Sciences, Medical)
- MonthlyIncome: Employee’s monthly income
- SalarySlab: Categorized salary ranges (e.g., Upto 5k, 5k-10k)
- Other Metrics: Factors like job satisfaction, work-life balance, years at the company, and performance ratings.
The dataset includes employees from various age groups (18 to 55+), different departments, job roles, and salary levels, which will be analyzed to identify factors leading to attrition.

## Approach
The following steps were followed in the project:
1. Data Preprocessing: Handled missing values, categorized variables like Age and Salary, and ensured data quality.
2. Exploratory Data Analysis (EDA): Investigated patterns of attrition based on various employee characteristics such as age, salary, department, education level, and job role.
3. Visualization: Created visualizations using Power BI to show attrition trends and provide insights into the factors influencing employee turnover.
4. Dashboard Creation: Developed an interactive dashboard with KPIs and charts to present the data in a user-friendly format, allowing users to explore attrition rates and analyze key trends.

## Models Used
This project is primarily an HR Analytics Dashboard where data visualizations help identify patterns and factors contributing to employee attrition. Although no machine learning models were implemented in this version of the dashboard, the data and insights provided could inform future development of predictive models like logistic regression, decision trees, or random forest classifiers to predict employee attrition.

## Results
The dashboard reveals the following insights:
- Total Employees: 1470 employees
- Attrition: 237 employees (16.1%)
- Average Age: 37 years
- Average Salary: $6.5K per month
- Average Years at Company: 7 years

## Key Insights:
- Attrition by Education: Life Sciences (38%) and Medical (27%) fields show the highest attrition.
- Attrition by Age: The highest attrition is observed in the 26-35 age group.
- Attrition by Salary: Employees earning up to $5K monthly show the highest attrition rates.
- Attrition by Years at Company: Attrition is highest among employees who have been with the company for 0-2 years, indicating possible issues with early retention.
- Attrition by Job Role and Satisfaction: Laboratory Technicians and Sales Executives have the highest attrition, with low job satisfaction scores.

## Outputs
The dashboard provides multiple interactive visualizations:
1. KPI Metrics: Total Employees, Attrition, Attrition Rate, Average Age, Average Salary, and Average Years at Company.
2. Charts:
- Attrition by Education
- Attrition by Age
- Attrition by Salary
- Attrition by Job Role
- Attrition by Years at Company
- Attrition by Gender
- Attrition by Job Role and Satisfaction Rate
3. Slicer: Allows users to filter data by department (Human Resources, Research & Development, Sales).

## Conclusion
The HR Analytics Dashboard offers valuable insights into employee attrition, helping organizations identify areas for improvement. The high attrition rates in specific job roles and salary groups suggest areas where retention efforts could be focused. Additionally, early-stage employees and certain educational backgrounds may require special attention in retention strategies.

#### Future improvements to the dashboard could include:
- Predictive modeling to anticipate future attrition based on the current data.
- More advanced interactive filters for deeper exploration of the dataset.
- This dashboard provides a foundation for HR departments to make data-driven decisions to reduce employee turnover.

