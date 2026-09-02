# 📊 HR Analytics Dashboard – Power BI

An interactive **HR Analytics Dashboard** built using Microsoft Power BI to analyze employee headcount, attrition, salary, age, recruitment sources, and workforce demographics.

## 📌 Project Overview

The **HR Dashboard** provides an interactive view of an organization's workforce and HR performance.

It helps HR teams and management understand:

* Employee headcount
* Employee attrition
* Attrition rate
* Average salary
* Average employee age
* Department-wise workforce distribution
* Age-wise employee distribution
* Gender and marital-status analysis
* Recruitment source performance
* Hiring trends over time
* Employee termination reasons

The dashboard uses interactive filters and drill-through functionality to make detailed employee-level analysis easier.

---

## 🎯 Project Objectives

* Analyze overall employee headcount.
* Monitor employee attrition and attrition rate.
* Understand workforce demographics.
* Compare employee distribution across departments.
* Analyze employee age groups.
* Evaluate recruitment sources.
* Identify hiring trends over time.
* Analyze employee termination reasons.
* Provide detailed employee information through drill-through analysis.
* Support HR decision-making using data visualization.

---

## 📊 Key Performance Indicators

The dashboard contains the following major KPIs:

| KPI                 | Description                                            |
| ------------------- | ------------------------------------------------------ |
| **Headcount**       | Total number of employees                              |
| **Attrition Rate**  | Percentage of employees who have left the organization |
| **Attrition Count** | Number of employees who left                           |
| **Average Salary**  | Average salary of employees                            |
| **Average Age**     | Average age of employees                               |

---

## 📈 Dashboard Visualizations

### 1. Department-wise Headcount

A bar chart is used to compare employee headcount across different departments.

**Purpose:**

* Identify departments with the highest workforce.
* Compare workforce distribution.
* Understand departmental staffing levels.

### 2. Age-wise Headcount

A column chart displays employee headcount across different age groups.

**Purpose:**

* Understand the age distribution of employees.
* Identify dominant employee age groups.
* Support workforce planning.

### 3. Attrition by Marital Status and Gender

The dashboard compares attrition using:

* Marital Status
* Gender

**Purpose:**

* Identify demographic patterns in employee attrition.
* Compare attrition between different employee groups.

### 4. Hiring Trend

A line chart analyzes employee headcount over the hiring timeline.

It includes:

* Date of Hire
* Headcount
* Cumulative Headcount

**Purpose:**

* Analyze hiring patterns over time.
* Understand workforce growth.
* Track cumulative employee additions.

### 5. Attrition Trend

A line chart displays attrition count over time.

**Purpose:**

* Identify periods with higher employee attrition.
* Analyze changes in attrition over the hiring timeline.
* Support HR retention strategies.

### 6. Recruitment Source Analysis

A column chart analyzes employee headcount by recruitment source.

**Purpose:**

* Compare different recruitment channels.
* Identify recruitment sources contributing the most employees.
* Support recruitment strategy decisions.

---

## 🔎 Interactive Filters

The dashboard provides slicers for:

* **Department**
* **Position**
* **Employment Status**
* **State**
* **Gender**

These filters allow users to interactively explore specific employee groups.

---

## 🔄 Drill-Through Analysis

The dashboard includes a dedicated **HR Dashboard – Detailed View** page.

The drill-through page provides detailed employee-level information including:

* Date of Hire
* Age
* State
* Citizenship
* Department
* Position
* Employment Status
* Manager Name

This allows users to move from high-level HR insights to detailed employee records.

---

## ❌ Termination Analysis

A dedicated tooltip visualization analyzes employee **termination reasons**.

The visualization compares:

**Termination Reason → Attrition**

This helps HR teams understand the major reasons employees leave the organization.

---

## 🛠️ Tools & Technologies

* **Microsoft Power BI Desktop**
* **Power Query**
* **DAX**
* **Data Modeling**
* **Data Visualization**
* **Interactive Slicers**
* **Drill-through**
* **Tooltips**

---

## 🔄 Data Analytics Workflow

```text
HR Dataset
     ↓
Data Cleaning
     ↓
Data Transformation
     ↓
Data Modeling
     ↓
DAX Measures
     ↓
KPI Creation
     ↓
Data Visualization
     ↓
Interactive HR Dashboard
     ↓
HR Insights & Decision Making
```

---

## 🧮 DAX Measures

The dashboard uses analytical measures such as:

* Headcount
* Attrition Rate
* Attrition Count
* Average Salary
* Average Age
* Attrition
* Cumulative Headcount

These measures enable dynamic calculations that respond to dashboard filters.

---

## 💡 Business Questions Answered

This dashboard can help answer questions such as:

1. How many employees are currently represented in the dataset?
2. What is the overall attrition rate?
3. How many employees have left the organization?
4. What is the average employee salary?
5. What is the average age of employees?
6. Which department has the highest headcount?
7. Which age groups contain the most employees?
8. How does attrition vary by gender?
9. How does attrition vary by marital status?
10. How has employee headcount changed over time?
11. Which recruitment sources contribute the most employees?
12. What are the most common termination reasons?
13. How can HR identify workforce and retention trends?

---

## 📁 Project Structure

```text
HR-Analytics-PowerBI/
│
├── README.md
├── HR-Dashboard.pbix
│
└── Screenshots/
    ├── HR-Dashboard.png
    ├── Detailed-View.png
    └── Termination-Analysis.png
```

---

## 🚀 How to Use

1. Install **Microsoft Power BI Desktop**.
2. Download the `.pbix` project.
3. Open the file using Power BI Desktop.
4. Refresh the dataset if required.
5. Use the available slicers to filter the dashboard.
6. Interact with charts to analyze HR metrics.
7. Use the drill-through functionality to view detailed employee information.

---

## 📚 Skills Demonstrated

This project demonstrates practical knowledge of:

* Power BI
* Data Analytics
* HR Analytics
* Data Cleaning
* Data Transformation
* Data Modeling
* DAX
* KPI Development
* Data Visualization
* Interactive Dashboard Design
* Slicers and Filters
* Drill-through Reports
* Tooltip Visualization
* Business Intelligence

---

## 🧠 Key Learning Outcomes

Through this project, the following concepts were applied:

* Building an end-to-end Power BI dashboard
* Creating meaningful HR KPIs
* Using DAX for analytical calculations
* Designing interactive reports
* Analyzing employee demographics
* Performing attrition analysis
* Visualizing recruitment trends
* Creating drill-through reports
* Presenting HR insights in a business-friendly format

---

## 📸 Dashboard Preview

Add screenshots of the dashboard to the repository:

```text
Screenshots/
├── HR-Dashboard.png
├── Detailed-View.png
└── Termination-Analysis.png
```

Example Markdown:

```markdown
![HR Dashboard](Screenshots/HR-Dashboard.png)
```

---

## ⭐ Conclusion

The **HR Analytics Dashboard** transforms employee data into an interactive Business Intelligence solution.

By combining **headcount, attrition, salary, age, recruitment, demographic, hiring, and termination analysis**, the dashboard provides HR teams with a centralized platform for understanding workforce trends and supporting data-driven decisions.

---

## 👨‍💻 Project Type

**HR Analytics | Data Analytics | Business Intelligence | Power BI**

---

"""

print("README content prepared successfully.")
curl = "/mnt/data/HR_Analytics_README.md"
with open(curl, "w", encoding="utf-8") as f:
f.write("""# 📊 HR Analytics Dashboard – Power BI

An interactive **HR Analytics Dashboard** built using Microsoft Power BI to analyze employee headcount, attrition, salary, age, recruitment sources, and workforce demographics.

## 📌 Project Overview

The **HR Dashboard** provides an interactive view of an organization's workforce and HR performance.

It helps HR teams and management understand:

* Employee headcount
* Employee attrition
* Attrition rate
* Average salary
* Average employee age
* Department-wise workforce distribution
* Age-wise employee distribution
* Gender and marital-status analysis
* Recruitment source performance
* Hiring trends over time
* Employee termination reasons

The dashboard uses interactive filters and drill-through functionality to make detailed employee-level analysis easier.

## 🎯 Project Objectives

* Analyze overall employee headcount.
* Monitor employee attrition and attrition rate.
* Understand workforce demographics.
* Compare employee distribution across departments.
* Analyze employee age groups.
* Evaluate recruitment sources.
* Identify hiring trends over time.
* Analyze employee termination reasons.
* Provide detailed employee information through drill-through analysis.
* Support HR decision-making using data visualization.

## 📊 Key Performance Indicators

| KPI                 | Description                                            |
| ------------------- | ------------------------------------------------------ |
| **Headcount**       | Total number of employees                              |
| **Attrition Rate**  | Percentage of employees who have left the organization |
| **Attrition Count** | Number of employees who left                           |
| **Average Salary**  | Average salary of employees                            |
| **Average Age**     | Average age of employees                               |

## 📈 Dashboard Visualizations

### Department-wise Headcount

A bar chart compares employee headcount across departments to identify workforce distribution and staffing levels.

### Age-wise Headcount

A column chart displays employee headcount across age groups to understand workforce demographics.

### Attrition by Marital Status and Gender

The dashboard compares attrition using marital status and gender to identify demographic patterns.

### Hiring Trend

A line chart analyzes employee headcount over the hiring timeline using Date of Hire, Headcount, and Cumulative Headcount.

### Attrition Trend

A line chart displays attrition count over time to identify periods with higher employee turnover.

### Recruitment Source Analysis

A column chart analyzes employee headcount by recruitment source to compare recruitment channels.

## 🔎 Interactive Filters

The dashboard provides slicers for:

* **Department**
* **Position**
* **Employment Status**
* **State**
* **Gender**

## 🔄 Drill-Through Analysis

The **HR Dashboard – Detailed View** page provides employee-level information including:

* Date of Hire
* Age
* State
* Citizenship
* Department
* Position
* Employment Status
* Manager Name

## ❌ Termination Analysis

A dedicated tooltip visualization analyzes employee **termination reasons** and their relationship with attrition.

## 🛠️ Tools & Technologies

* **Microsoft Power BI Desktop**
* **Power Query**
* **DAX**
* **Data Modeling**
* **Data Visualization**
* **Interactive Slicers**
* **Drill-through**
* **Tooltips**

## 🔄 Data Analytics Workflow

```text
HR Dataset
     ↓
Data Cleaning
     ↓
Data Transformation
     ↓
Data Modeling
     ↓
DAX Measures
     ↓
KPI Creation
     ↓
Data Visualization
     ↓
Interactive HR Dashboard
     ↓
HR Insights & Decision Making
```

## 🧮 DAX Measures

The dashboard uses analytical measures such as:

* Headcount
* Attrition Rate
* Attrition Count
* Average Salary
* Average Age
* Attrition
* Cumulative Headcount

## 💡 Business Questions Answered

1. How many employees are represented in the dataset?
2. What is the overall attrition rate?
3. How many employees have left?
4. What is the average employee salary?
5. What is the average employee age?
6. Which department has the highest headcount?
7. Which age groups contain the most employees?
8. How does attrition vary by gender?
9. How does attrition vary by marital status?
10. How has employee headcount changed over time?
11. Which recruitment sources contribute the most employees?
12. What are the most common termination reasons?

## 📁 Project Structure

```text
HR-Analytics-PowerBI/
│
├── README.md
├── HR-Dashboard.pbix
│
└── Screenshots/
    ├── HR-Dashboard.png
    ├── Detailed-View.png
    └── Termination-Analysis.png
```

## 🚀 How to Use

1. Install **Microsoft Power BI Desktop**.
2. Download the `.pbix` project.
3. Open the file using Power BI Desktop.
4. Refresh the dataset if required.
5. Use the slicers to filter the dashboard.
6. Interact with charts to analyze HR metrics.
7. Use drill-through to view detailed employee information.

## 📚 Skills Demonstrated

* Power BI
* Data Analytics
* HR Analytics
* Data Cleaning
* Data Transformation
* Data Modeling
* DAX
* KPI Development
* Data Visualization
* Interactive Dashboard Design
* Slicers and Filters
* Drill-through Reports
* Tooltip Visualization
* Business Intelligence

## 🧠 Key Learning Outcomes

This project demonstrates how to build an end-to-end Power BI HR dashboard, create meaningful KPIs, use DAX for analytical calculations, analyze employee demographics and attrition, visualize recruitment trends, and present HR insights in a business-friendly format.

## 📸 Dashboard Preview

Add screenshots to:

```text
Screenshots/
├── HR-Dashboard.png
├── Detailed-View.png
└── Termination-Analysis.png
```

Example:

```markdown
![HR Dashboard](Screenshots/HR-Dashboard.png)
```

## ⭐ Conclusion

The **HR Analytics Dashboard** transforms employee data into an interactive Business Intelligence solution. By combining **headcount, attrition, salary, age, recruitment, demographic, hiring, and termination analysis**, it provides HR teams with a centralized platform for understanding workforce trends and supporting data-driven decisions.

