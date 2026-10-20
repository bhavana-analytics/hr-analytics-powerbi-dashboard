# **HR Analytics Report**

## **Overview**

The HR Analytics Report is a Power BI report designed to provide HR teams and business stakeholders with a consolidated view of workforce composition, compensation, employee performance, and attrition trends. The report is structured across two pages, each focused on a distinct area of analysis, allowing for clear insights without overcrowding a single view.


### **Page 1: HR Workforce & Compensation Analysis**

**KPI Cards**

KPI Card 1 — Total Employees Shows the total number of employees in the organization.

KPI Card 2 — Average Salary Shows the average salary across all employees.

KPI Card 3 — Average Experience Shows the average work experience of employees.

Visualizations

**1. Workforce Composition by Department & Gender — Treemap** The Treemap visualizes workforce composition across departments and genders, showing how employees are distributed within each department. The dataset contains 50 employees across five departments, with 10 employees in each and an overall balanced gender distribution of 25 females and 25 males.

**2. Average Salary by Department — Clustered Column Chart** The Clustered Column Chart compares the average salary across different departments. It helps identify which departments have higher or lower average salaries and provides a clear comparison of compensation levels across the organization.

**3. Age Distribution — Area Chart** The Area Chart shows how employees are distributed across different age groups. It helps identify which age ranges have the highest and lowest representation within the workforce, providing a clear view of the organization's workforce age profile.

**4. Hiring Trend — Line Chart** The Line Chart shows employee hiring patterns over time based on the Hire_Date field. It helps identify periods with higher or lower hiring activity and provides an overview of how the organization's workforce has grown over time.

**5. Average Employee Experience by Department — Clustered Bar Chart** The Clustered Bar Chart compares the average employee experience across different departments. It helps identify which departments have employees with higher or lower average experience, providing a clear comparison of experience levels across the organization.



![Page 1](https://github.com/user-attachments/assets/3c50d5d2-8656-49b4-a412-c3764e3d5b1b)


### **Page 2: HR Performance & Attrition Analysis**

**KPI Cards**

KPI Card 1 — Attrition Count Shows the total number of employees who have left the organization.

KPI Card 2 — Attrition Rate Shows the percentage of employees who have left the organization.

KPI Card 3 — High Performers Shows the total number of employees classified as high performers.

**Visualizations**

**1. Performance Distribution by Department — Matrix** This visual compares the distribution of Low, Average, and High performers across departments. It helps identify performance patterns within each department.

**2. Attrition by Department — Clustered Bar Chart** The Clustered Bar Chart compares employee attrition across departments, helping identify which departments have the highest and lowest attrition levels.

**3. Attrition by Gender — Donut Chart** The Donut Chart shows the distribution of attrition by gender. It helps identify whether attrition is higher among male or female employees.

**4. Attrition by Performance — Ribbon Chart** The Ribbon Chart shows how attrition varies across Low, Average, and High performance groups. It helps identify which performance category contributes the most to employee attrition.

**5. Attrition by Age Group — Clustered Column Chart** The Clustered Column Chart compares attrition across different age groups. It helps identify which age groups have higher employee turnover.

### **Interactive Slicers**

The report includes interactive slicers for Department, Hire Date, Performance, and Gender. These slicers allow users to dynamically filter the report and explore workforce, compensation, performance, and attrition insights based on selected employee characteristics.

### **Tools & Technologies**
-  Power BI Desktop
-  DAX (Data Analysis Expressions) for calculated measures
-  Custom theme and interactive slicers

### **Notes**
-  The dataset does not contain employee names or other personally identifiable information; it is intended for analytical and demonstration purposes.
-  The report and its measures can be adapted for use with other HR datasets.
