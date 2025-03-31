# Employee Attrition Dashboard

This project presents an interactive Power BI dashboard built to analyze and visualize employee attrition trends within an organization. By leveraging historical HR data, the dashboard helps identify key drivers of attrition and offers actionable insights to improve workforce retention strategies.

---

## Objective

To understand and reduce employee attrition by identifying patterns and correlations across multiple employee dimensions such as demographics, job role, satisfaction levels, tenure, and commute distance.

---

## Dashboard Output

![image](https://github.com/user-attachments/assets/8866f0ef-dcdb-4965-bb56-f4cd763be6c6)
![image](https://github.com/user-attachments/assets/973694aa-9284-4215-9846-487890fea2c4)



---

## Tools and Technologies

- **Power BI Desktop** – For data modeling, dashboard creation, and interactivity
- **Excel** – For initial data sourcing and preprocessing
- **DAX (Data Analysis Expressions)** – For calculated fields and measures
- **Data Modeling** – Relationships, hierarchies, and filters
- **Power Query** – For data cleaning and transformations

---

## Dataset Overview

- **Total Records**: 2,925 employee records
- **Key Fields Included**:
  - Employee ID, Gender, Department, Job Role
  - Years at Company, Education Level
  - Distance from Home
  - Employee Satisfaction
  - Attrition (Yes/No)
  - Manager Details

---

## Dashboard Features

- **Attrition Overview**
  - Total Employees
  - Attrition Rate (%)
  - Count of Employees Who Left
- **Attrition by Demographics**
  - Gender-wise attrition comparison
  - Attrition by Education Level
- **Attrition by Organizational Role**
  - By Department
  - By Job Role
  - By Manager
- **Attrition by Behavior/Engagement**
  - Employee Satisfaction Levels
  - Years at Company
  - Distance from Work

Each visual is interactive and supports filtering, highlighting correlations across multiple dimensions simultaneously.

---

## Key Insights

- Highest attrition rates observed among Sales Executives and Research Scientists.
- Employees dissatisfied or very dissatisfied are significantly more likely to leave.
- Commute distance plays a notable role; those living very far show higher attrition.
- Certain managers have disproportionately high attrition in their teams, indicating potential leadership issues.

---

## How to Run This Project

1. **Download or Clone** this repository.
2. Open the `Attrition Dashboard.pbix` file in Power BI Desktop.
3. Ensure that the `Dataset.xlsx` is in the same directory, or reconnect it if prompted.
4. Interact with filters, slicers, and visuals to explore the data from different perspectives.

---

## Lessons Learned

- Developed expertise in building business dashboards from scratch using real-world HR datasets.
- Strengthened knowledge of Power BI DAX and data relationships.
- Learned best practices in choosing the right visual types to communicate specific insights.
- Gained appreciation for the importance of understanding business context before diving into analysis.

---

## Recommendations

- Introduce flexible work arrangements or remote work options to address commute-related attrition.
- Launch employee satisfaction improvement initiatives, especially targeting high-risk departments.
- Provide training and support to managers with high team attrition to improve engagement.
- Use predictive modeling in the future to proactively identify employees at high risk of attrition.

---

## Future Enhancements

- Integrate **time-series analysis** to track attrition trends over months/years.
- Add **predictive modeling** using Power BI and Python for proactive HR planning.
- Incorporate **survey feedback** and sentiment analysis for a more comprehensive view of dissatisfaction.

