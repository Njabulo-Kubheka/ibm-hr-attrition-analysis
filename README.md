# IBM HR Analytics — Employee Attrition Analysis

An exploratory data analysis (EDA) of IBM's HR dataset to identify the key factors driving employee attrition and provide actionable business recommendations.

📓 **Live Notebook:** [View on Kaggle](https://www.kaggle.com/code/njabulokubheka/ibm-hr-attrition-analysis-njabulo-kubheka)

---

## Overview

Employee attrition is costly for any business — recruiting and training a replacement can cost up to twice an employee's annual salary. This project analyses 1,470 employee records across 35 variables to answer one core question:

**Why are employees leaving, and what can the business do about it?**

---

## Dataset

| Property | Detail |
|---|---|
| Source | IBM HR Analytics Employee Attrition & Performance (Kaggle) |
| Records | 1,470 employees |
| Features | 35 columns |
| Missing values | 0 |
| Key columns | Age, Department, JobRole, MonthlyIncome, Attrition, JobSatisfaction, OverTime, YearsAtCompany |

---

## Tools Used

| Tool | Purpose |
|---|---|
| Python 3 | Core analysis language |
| Pandas | Data manipulation and exploration |
| Matplotlib | Data visualisation |
| Seaborn | Statistical charts |
| Jupyter Notebook (Kaggle) | Development environment |

---

## Key Findings

### 1. Overall Attrition Rate — 16.1%
237 out of 1,470 employees left — a significant attrition rate that signals a retention problem worth investigating.

### 2. Department
Research & Development has the highest number of employees leaving, despite being the largest department.

### 3. Job Role
Laboratory Technicians, Sales Executives, and Research Scientists account for the most attrition by role.

### 4. Age Group
Employees aged **26–35** leave the most — early career professionals are the hardest to retain.

### 5. Compensation Gap 💰
| Group | Average Monthly Income |
|---|---|
| Employees who stayed | R6,833 |
| Employees who left | R4,787 |
| **Difference** | **R2,046** |

Low compensation is one of the strongest drivers of attrition in this dataset.

### 6. Overtime
- Employees working overtime: **30.5% attrition rate**
- Employees not working overtime: **10.4% attrition rate**

Working overtime more than doubles the probability of an employee leaving.

### 7. Job Satisfaction
Employees with the lowest job satisfaction score (Level 1) have the highest attrition rate — dissatisfied employees leave.

### 8. Tenure
Attrition peaks at **Year 1** — new employees are the most at risk of leaving early, suggesting an onboarding problem.

---

## Business Recommendations

Based on the analysis, the business should prioritise:

1. **Review compensation** for Laboratory Technicians and Sales Executives — the R2,046 income gap between leavers and stayers is too large to ignore
2. **Reduce overtime** demands, especially in the Research & Development department
3. **Improve onboarding** — year 1 attrition is the highest, meaning new hires need better early engagement and support
4. **Monitor job satisfaction** scores regularly as an early warning system for flight risk employees
5. **Focus retention efforts on 26–35 age group** — targeted development programmes and career progression paths

---

## Visualisations

The notebook includes 7 visualisations:
- Attrition by Department (bar chart)
- Attrition by Job Role (horizontal bar chart)
- Attrition by Age Group (bar chart)
- Monthly Income vs Attrition (box plot)
- Attrition by Overtime Status (grouped bar chart)
- Attrition by Job Satisfaction Level (bar chart)
- Attrition by Years at Company (line chart)
- Summary Dashboard (all 6 charts in one figure)

---

## How to Run

1. Open the [Kaggle Notebook](https://www.kaggle.com/code/njabulokubheka/ibm-hr-attrition-analysis-njabulo-kubheka)
2. Click **Copy & Edit** to run it yourself
3. All dependencies are pre-installed in the Kaggle environment

---

## Author

**Njabulo Kubheka**
BCom Information Systems — University of the Western Cape
[LinkedIn](https://www.linkedin.com/in/njabulo-kubheka) | [GitHub](https://github.com/Njabulo-Kubheka) | [Kaggle](https://www.kaggle.com/njabulokubheka)
