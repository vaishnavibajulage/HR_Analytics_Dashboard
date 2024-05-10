
# HR_ANALYTICS_DASHBOARD


### Dashboard Link :https://github.com/vaishnavibajulage/HR_Analytics_Dashboard/blob/main/Employee's_Analytics.pbix

## Problem Statement

This HR analytics dashboard offers a holistic view of employee dynamics within the organization, facilitating real-time insights into key performance indicators and trends essential for effective human resource management. Through this dashboard, stakeholders can closely monitor and analyze various aspects of employee engagement and retention, empowering them to make data-driven decisions.

The dashboard provides comprehensive metrics such as total number of employees, average age, average salary, distribution of job roles, and attrition rate. It allows stakeholders to delve into deeper insights by showcasing reasons for employee attrition, including factors such as career advancement opportunities, work-life balance, compensation, and organizational culture. Additionally, the dashboard offers insights into the tenure of departing employees, shedding light on whether there are any patterns or trends in terms of the duration of employment.

One notable feature of this dashboard is its ability to segment and analyze employee data based on various parameters such as department, tenure, and performance ratings. By incorporating predictive analytics models, the dashboard can also forecast potential attrition risks, enabling proactive interventions to mitigate turnover.

In summary, this HR analytics dashboard serves as a powerful tool for HR professionals and organizational leaders, providing them with actionable insights to optimize employee retention strategies, foster a positive work environment, and ultimately drive organizational success."

### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" 

- Step 3 : In the report view, under the view tab, theme was selected.

- Step 4 : Since the data contains various Quaters, thus in order to represent Quaters, a new visual was added using the treeMap  in the visualizations pane in report view.

![Snapshort 1](https://github.com/vaishnavibajulage/HR_Analytics_Dashboard/assets/83158414/afe3fc1b-1f18-43da-93ec-251f038e736a)



- Step 5 : Visual filters (Slicers) were added for sort the department 

![Snapshort 2](https://github.com/vaishnavibajulage/HR_Analytics_Dashboard/assets/83158414/0ba55c4f-5289-4246-ad5d-b7f5f4990555)


           Using visual level filter from the filters pane, basic filtering was used & null values were unselected for consideration into average calculation.
           
- Step 6 : In the report view, under the insert tab, One text boxe added to the canvas, in that  "HR ANALYTICS DASHBOARD"  was mentioned .
 
- Step 7 : New measure was created to find attrition rate

Following DAX expression was written for the same,
        
AttritionRate = SUM('HR_Analytics (1)' [AttritionCount])/SUM('HR_Analytics (1)'[EmployeeCount])

![snapshort](https://github.com/vaishnavibajulage/HR_Analytics_Dashboard/assets/83158414/f1858946-41a5-4d4a-a964-5d6945521a7d)




# Snapshot of Dashboard (Power BI Service)
![Dashboard](https://github.com/vaishnavibajulage/HR_Analytics_Dashboard/assets/83158414/bf474e8a-8573-4706-885c-81d10137b800)


 
 

# Insights

A one page report was created on Power BI Desktop 

Following inferences can be drawn from the dashboard;

### [1] Total Number count of Employee = 546

Employee attrition = 1470

attrition rate = 16.12

Employee Avg salary = 6.50k

Number of Avg year they worked =7.01k

Employee Avg Age = 36.92

Male customers are contributing more in attrition 123, female 66




          

    
 
  
  
  

 # HR_Analytics_Dashboard
