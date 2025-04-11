# Project Overview:

This Project tell us about the actionable insights regarding the crowdfunding platforms and their impact on the individual projects following the different parameters. It aims at the analysis of key performance indicator and give the data driven insights to take critical business decisions.

# Problem Statement
This project aims to analyze the key factors that drive crowdfunding campaign success and understand performance across categories, locations, and time. This project provides and exposure to data cleaning and validation , data importing to different visualization platforms and analyze the data set to find out the KPI’S using SQL. Uncover insights to support crowd funding Operations ,Design interactive Dashboard and reports to highlights the metrics and findings.

# Technical exposure
Excel: Data cleaning, validation, preliminary analysis ,and data modeling

SQL: Data extraction, querying, and transformation.

Power BI: Visualizing KPIs and generating interactive dashboards.

Tablaeu: Visualizing KPIs and generating interactive dashboards.

# Data Transformation & Modeling
• Conversion of epoch dates to natural time.

• Building a comprehensive calendar table to facilitate time-based analysis.

• Currency conversion of goal amounts to USD.

• Date range spanning from the minimum to maximum project creation dates.

• Columns created: Year, Month number, Month full name, Quarter, Year-Month, Weekday, Financial Month, and Financial Quarter.

# KEY PERFORMACE INDICATORS (KPI)
Total Number of Projects based on outcome
Total Number of Projects based on Locations
Total Number of Projects based on Category
Total Number of Projects created by Year , Quarter , Month
Amount Raised
Number of Backers
Avg. Number of Days for successful projects
Successful Projects
Percentage of Successful Projects by Category
Percentage of Successful projects by Goal Range

# Steps followed
Step 1 : Load data into Excel, load data into Power BI Desktop, and import data to MySQL. dataset is a csv file for Power BI and MySQL.
Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
Step 4 : It was observed that errors were present in few columns and were removed.
Step 5 : In the report view, under the view tab, theme was selected.
Step 6 : Visual filters (Slicers) were added for fields named "State", "Quarter" & "Timeline was inserted".
Step 7 : By default, while calculating average, blank values are ignored.
Step 8 : Cards were used in Power BI to mention the values of Number of Backers, Successful Projects, Average number of days for Successful Projects.
Step 9 : Custom column was created in which, epoch dates were converted into date.
Step 10 : Worked on all KPI's and created Dashboard in Excel and Power BI.
Step 11 : Executed queries in MySQL.

# Snapshot of Dashboard (Excel)

![image](https://github.com/user-attachments/assets/ee02a18f-3c41-4be5-a6af-7ea433d7fbb0)

#Snapshot of Dashboard (Power BI)

![image](https://github.com/user-attachments/assets/3e9a9892-33c8-40b3-9f1d-0a8be6eec486)

#Snapshot of Dashboard (Tableau)
![image](https://github.com/user-attachments/assets/d9be4b88-5c7d-4548-8b93-cc3475637951)



# Datasets used
Crowdfunding_Category

Crowdfunding_Creator

Crowdfunding_Location

Crowdfunding_Projects_1


# Insights
Categories like Product Design and Tabletop Games have the highest number of successful projects.
Overall success rate is 37.16% with significant failing project. Thus, collaboration with backers and creators should be strong enough to provide basic resources like workshops, templates and effective training for creators to prepare their campaigning plans.
Although we observe that 45 million backer are engaged with the projects, retention of the backers are the major aspect to project completion. Creation of loyalty programs, access to premium project and frequent communication with the top backers will help achieve backers retention.

# Conclusion
The analysis of crowdfunding projects reveals that success is influenced by factors such as category selection, funding goal size, and timing. Campaigns in categories like product design and tabletop games are more likely to succeed, especially if they set realistic funding goals between 1K and 10K. Launching campaigns during high-performing months like April and August, while drawing inspiration from top projects, can significantly improve outcomes. Creators should focus on backer engagement, clear messaging, and realistic goals to maximize their chances of success.

