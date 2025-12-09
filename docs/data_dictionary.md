# Data Dictionary – HR Attrition Analytics Dataset

This document describes the fields used in the HR Attrition Analytics Dashboard.

| Column Name               | Description                                                                 | Data Type | Example              |
|---------------------------|-----------------------------------------------------------------------------|----------|----------------------|
| EmployeeNumber            | Unique identifier for each employee                                        | Integer  | 1001                 |
| EmployeeCount             | Constant employee counter (often all 1)                                   | Integer  | 1                    |
| Age                       | Employee age in years                                                      | Integer  | 34                   |
| Gender                    | Gender of the employee                                                     | Text     | Male / Female        |
| MaritalStatus             | Marital status of the employee                                             | Text     | Single / Married     |
| Department                | Department in which the employee works                                     | Text     | Sales                |
| JobRole                   | Job title/role within the company                                          | Text     | Sales Executive      |
| JobLevel                  | Internal job level / band (seniority)                                     | Integer  | 2                    |
| BusinessTravel            | Frequency of business travel                                               | Text     | Travel_Rarely        |
| Education                 | Education level (1–5 scale)                                                | Integer  | 3                    |
| EducationField            | Field of study / specialization                                            | Text     | Life Sciences        |
| DistanceFromHome          | Distance between home and office (in km or miles)                          | Integer  | 12                   |
| TotalWorkingYears         | Total years of professional experience                                     | Integer  | 8                    |
| YearsAtCompany            | Total years the employee has worked at the company                         | Integer  | 5                    |
| YearsInCurrentRole        | Years spent in the current role                                            | Integer  | 3                    |
| YearsWithCurrManager      | Years working with the current manager                                     | Integer  | 2                    |
| YearsSinceLastPromotion   | Years since last promotion                                                 | Integer  | 1                    |
| MonthlyIncome             | Employee’s current monthly salary                                          | Numeric  | 6500                 |
| MonthlyRate               | Standard monthly rate (if available)                                       | Numeric  | 14000                |
| HourlyRate                | Hourly pay rate                                                            | Numeric  | 75                   |
| DailyRate                 | Daily pay rate                                                             | Numeric  | 800                  |
| PercentSalaryHike         | Percentage salary increase over last hike                                  | Numeric  | 13                   |
| StockOptionLevel          | Stock option level allocated to employee (0–3)                             | Integer  | 1                    |
| OverTime                  | Whether employee works overtime regularly (Yes/No)                         | Text     | Yes                  |
| Over18                    | Whether employee is over 18 years of age (Y/N)                             | Text     | Y                    |
| Attrition                 | Indicates whether employee left the company (Yes/No)                       | Text     | Yes                  |
| PerformanceRating         | Latest performance rating (1–4 scale)                                     | Integer  | 3                    |
| EnvironmentSatisfaction   | Satisfaction with work environment (1–4; 1=Low, 4=Very High)               | Integer  | 4                    |
| JobSatisfaction           | Overall job satisfaction (1–4 scale)                                      | Integer  | 3                    |
| JobInvolvement            | Level of involvement in job (1–4 scale)                                   | Integer  | 3                    |
| RelationshipSatisfaction  | Satisfaction with relationships at work (1–4 scale)                       | Integer  | 2                    |
| WorkLifeBalance           | Rating of work–life balance (1–4 scale)                                   | Integer  | 3                    |
| TrainingTimesLastYear     | Number of trainings attended in the last year                              | Integer  | 3                    |
| StandardHours             | Standard working hours per week (often constant, e.g., 80)                 | Integer  | 80                   |
| NumCompaniesWorked        | Number of companies the employee has worked for                            | Integer  | 2                    |
| SalaryBand (derived)      | Salary group bucket used in the dashboard (e.g., `Upto 5k`, `5k–10k`)     | Text     | Upto 5k              |
| AgeBand (derived)         | Age group bucket used in visuals (e.g., `18–25`, `26–35`)                 | Text     | 26–35                |
| TenureBand (derived)      | Years-at-company bucket for analysis (e.g., `0–2`, `3–5`, `6–10`, `10+`)  | Text     | 3–5                  |


