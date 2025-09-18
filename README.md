# VitaTrack-Wellness-Dashboard
<img width="1536" height="1024" alt="ChatGPT Image Sep 18, 2025, 01_11_10 PM" src="https://github.com/user-attachments/assets/b32f85cf-5ebd-46fb-b5ac-025bc6c21366" />

## Table of contents :
-  [Problem statement](#problem-statement)
-  [Data Source](#data-source)
-  [Data Preparation](#data-preparation)
-  [Data Modelling](#data-modelling)
-  [Data Visualization Dashboard](#data-visualization-dashboard)
-  [Insights](#insights)

## Problem statement :
<img width="703" height="594" alt="Screenshot 2025-09-18 132906" src="https://github.com/user-attachments/assets/9396d683-1bf8-4052-86d6-58d692c7ca84" />

## Data Source :
Dataset used for this task was presented by [PW-Skills](#pw-skills).

**Dataset:** [health_activity_data](./health_activity_data.csv)

## Data preparation :
Completed the Data transformation in Power Query and the dataset loaded into Microsoft Power BI Desktop for modeling.

Health activity data:
-  **`health_activity_data`** which has **`25 columns and 999+ rows`** of observation

Data Cleaning for the dataset was done in the power query editor as follows:

-  Removed Unnecessary data
-  Handle null
-  Each of the columns in the table were validated to have the correct data type

## Data Modelling :
The dataset was cleaned and transformed, it was ready to the data modeled.
-  the **`measure table`** and **`call centre trends dataset`** tables as show below :-

  <img width="1082" height="737" alt="Screenshot 2025-09-18 132228" src="https://github.com/user-attachments/assets/3a83e518-dacd-4aaa-bc24-db95a488d2ba" />

## Data Visualization Dashboard :
Data visualization for the data analysis (DAX) was done in Microsoft Power BI Desktop.

Shows visualizations from Call Center Trends :
<h1 align="center">Health Insights (Introduction)</h1>


<img width="1326" height="719" alt="Screenshot 2025-09-18 125918" src="https://github.com/user-attachments/assets/182fe430-2aef-45e8-82b5-72975c90f834" />


<h1 align="center">Health Insights (Overview)</h1>

<img width="1358" height="754" alt="Screenshot 2025-09-18 131311" src="https://github.com/user-attachments/assets/cf11bac8-9b0e-4971-99cb-1c5b5570715c" />


<h1 align="center">Health Insights (Sleep And Activity Correlation)</h1>


<img width="1355" height="771" alt="Screenshot 2025-09-18 131339" src="https://github.com/user-attachments/assets/438c90a9-48eb-4b14-a9ec-c354d707627b" />


## Insights :

VitaTrack Wellness Dashboard analyzes lifestyle habits and their impact on health through data on BMI, sleep, and exercise. ​

1-	Lifestyle Habits & Its Impact on Health :
-  VitaTrack Wellness provides smart health monitoring solutions for lifestyle management. ​
-  The dashboard collects health metrics to identify risks and promote well-being. ​
-  Key metrics include BMI, sleep patterns, exercise frequency, and alcohol consumption.
-  
2-	BMI Trends :
-  Average BMI for males is 26.6 and for females is 26.9. ​
-  49.7% of males and 50.3% of females fall into the overweight category.
-  BMI trends vary across age groups, with the highest average in the 46-60 age group.

3-	Heart Disease Distribution :
-  90.7% of participants reported no heart disease.
-  Alcohol consumption correlates with heart disease risk, with higher rates in drinkers. ​
-  Sleep goals also impact heart disease prevalence, with significant differences noted.

4-	Sleep & Activity Correlation :
-  Average hours of sleep and exercise hours are analyzed for heart disease correlation.
-  Adequate sleep (6-8 hours) is linked to better exercise performance.
-  Daily steps and sleep hours show a relationship with heart disease presence.

5-	Smoking & Alcohol Impact :
-  Smokers show higher cardiovascular risks compared to non-smokers.
-  Average systolic blood pressure is higher in drinkers, with variations based on consumption levels.
-  Alcohol consumption affects average calories intake and overall health metrics.

6-	Daily Steps vs Hours of Sleep :
-  Average daily steps decrease with age, with 2.35K steps for ages 46-60.
-  Heart disease presence is analyzed against daily steps and sleep hours.
-  Recommendations for daily steps align with WHO guidelines for health maintenance.


