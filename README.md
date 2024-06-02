# ASK A MANAGER SALARY SURVEY ANALYSIS 


###
Welcome to the **Ask A Manager Salary Survey Analysis** repository. This project analyzes salary data collected from a diverse range of employees across various industries. The dataset includes information on age groups, gender, industry, years of experience, annual salary, educational level and race

###
You can interact with the report [HERE](https://github.com/Nkemjika-123/nkemjika-omazi/blob/main/Visualization-Salary%20Survey%20Report.pbix)


## Introduction
The **Ask A Manager Salary Survey Analysis** project aims to provide valuable insights into salary trends and disparities within the workforce. By examining factors such as age, gender, industry, years of experience, annual salary, educational level and race, this analysis helps organizations make informed decisions regarding compensation, hiring, and diversity initiatives.

## Objectives
+ Understand Salary Trends: Identify how different factors such as industry, years of experience, and demographics influence salary levels.

+ Identify Disparities: Highlight any significant disparities in salary based on gender, educational level, race, or other demographic factors.

+ Support Decision Making: Provide actionable insights that can aid organizations in developing fair and competitive compensation strategies.

  ## Data Source
The data used for this project was from [HERE](https://docs.google.com/spreadsheets/d/1vB5eAhH_93EKUyu-AQHQ68S3ULsEMO3zqkEf1LmIuoU/edit#gid=1625408792)

## Task
Which Industry Pays the Most?
+ Analyze and compare average salaries across different industries.
+ Visualize industry-wise salary distributions.

Salary Growth with Years of Experience:
+ Explore how salaries change with increasing years of experience.
+ Identify trends in salary growth over the years.

Geographical Salary Variations:
+ Compare salaries for the same role in different locations. 
+ Visualize regional salary differences.

Gender and Experience Impact on Salaries:
+ Investigate how salaries differ based on gender and years of experience. 
+ Examine potential gender-based salary gaps.

Correlation of Race and Education with Salary:
+ Assess the correlation between race, education level, and salary.
+ Identify any patterns or disparities.

Total Work Experience vs. Field-Specific Experience:
+ Determine if there's a "sweet spot" in the balance between total work experience and years in a specific field.
+ Explore how this balance correlates with salary.

## Data Preparation and Transformation
To prepare dataset for analysis, the data was opened in Excel. This dataset was extremely dirty and so the Data cleaning was done in excel and power query. Detailed steps are below:
 1.	Renamed all the columns to the appropriate names eg **What country do you work in? was renamed to “Country”**
 2.	Changed all the countries to a standard name eg **United States, America etc was renamed to US**
 3.	Values in Industry column was modified to a general name eg **Education (Higher Education) was modified to Education, 
      Everything under academic and academia was modified to academia**   
 4.	In the gender column, I modified all the **“Other or prefer not to answer” to “Prefer not to answer”**
 5.	I modified the race column to “**Race Type**” and named all those that belong to one race “**monoracial**”, those that belong to two races, “**biracial**” and those that belong to two or more “**multiracial**”, i did this by creat to ing another column using "**column from examples**" under the "**add column tab**"
 6.	I also put N/A in all the blanks and removed duplicated
 7.	At the end of the data cleaning I had 27832 rows and 15 columns

## Data Exploration and Visualization
1. I also created some measures to help me add KPIs like "**Row Count**", "**Average Anunal Salary**" to the report.

2. I also added some slicers to be able to easily show correlation between "**Race**" and "**Education**" with "**Salary**"

   ![Ask A ManagerSalarySurvey1](https://github.com/Nkemjika-123/nkemjika-omazi/assets/152037119/8571a7f8-0735-41c3-80cf-cfd0994d3d22)


![Ask A ManagerSalarySurvey2](https://github.com/Nkemjika-123/nkemjika-omazi/assets/152037119/afe85667-60f2-41de-875e-7c9e159e5705)

You can interact with the report [HERE](https://github.com/Nkemjika-123/nkemjika-omazi/blob/main/Visualization-Salary%20Survey%20Report.pbix)

## Analysis and Findings/Insights
+	Based on the analysis, IPR industry pays the most with an average annual salary of 1M.
+	Employees between the ages of 21 – 30 had the highest average salary probably because they were more efficient and were promoted more often with pay rise.
+	Indonesia had the highest average salary, specifically those whose job role was Regional Operations followed by the Researchers.
+	Females had longer years of experience than males.
+	On the average, the men earned more than any other gender followed by the women
+	Majority of the monoracials had college degree as their highest degree gotten.
+	For the Biracials, those which PHD which is the highest level of education, have significantly higher salaries than others and they mostly belong to two races.
+	For the Monoracial and Multiracial, those with college degrees earned the highest salaries.

## Recommendations
Since it was observed that the females stayed longer in the organization, I’ll suggest that the males be given some incentives to encourage them to stay longer. 

## Presentation
Visualization was done in PowerBi

###
You can interact with the report [HERE](https://github.com/Nkemjika-123/nkemjika-omazi/blob/main/Visualization-Salary%20Survey%20Report.pbix)
