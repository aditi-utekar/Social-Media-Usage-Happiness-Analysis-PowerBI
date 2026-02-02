# 📊Social Media Usage & Happiness Analysis Dashboard Using Power BI

## Project Overview
This Power BI dashboard analyzes the relationship between social media usage, lifestyle habits, and happiness levels across different age groups and genders.
The goal of this project is to identify patterns between:
- Screen time
- Exercise frequency
- Sleep quality
- Stress levels
- Social media platform usage
- Overall happiness index

## Problem Statement
How do social media usage and lifestyle factors (exercise, sleep, stress) influence overall happiness across different demographics?
This dashboard helps uncover:
- Which platforms are associated with higher happiness levels
- How exercise frequency impacts happiness
- The relationship between sleep quality and age groups
- Gender-based differences in happiness trends

## 📂 Dataset Description
The dataset includes the following fields:
- User Id
- Age
- Gender
- Social Media Platforms
- Daily Screen Time
- Sleep Quality
- Days Without Social Media
- Exercise Frequency
- Stress Level
- Happiness Index

## ⚙️ Project Process
1. Data Collection
- Imported dataset into Power BI Desktop (CSV source)

2. Data Cleaning (Power Query)
- Checked for missing/null values
- Standardized categorical columns (Gender, Sleep Quality, Platform names)
- Verified correct data types (numeric, text, categorical)
- Removed duplicates (if any)

3. Data Modeling
Ensured proper column formatting
Created calculated measures using DAX

4. DAX Measures Created
- Average Screen Time (Hrs)
- Average Exercise Frequency
- Average Sleep Quality
- Average Happiness Index
- Average Stress Level
- User Count
- Age Group
- Sleep Quality Index(Poor,Moderate,Good)

5.Dashboard Design

Created KPI cards to show:
- Average Screen Time(hrs)
- Average Exercise Frequency
- Average Happiness Index
- Average Sleep Quality
- Average Stress Level

Used:
- Bar Chart - Happiness Index By Social Media Platform
- Donut Chart - User Count By Social Media Platform
- Line Chart - Happiness Vs Exercise Frequency By Gender
- Clustered Column Chart - Sleep Quality By Age Group

Added slicers for:
- Age Group
- Gender

Applied consistent colour theme and layout formatting.

📊 **Key Insights**
<ul>
<li> LinkedIn shows the highest average happiness index among platforms.
<li> Increased exercise frequency is positively correlated with higher happiness levels.
<li> Moderate sleep quality dominates across most age groups.
<li> Users aged 35–44 show high moderate sleep counts.
<li> Stress levels vary moderately across demographics.
</ul>

🛠 **Tools & Technologies Used**
- Power BI Desktop
- Power Query
- DAX
- Data Modeling
- Data Visualization Best Practices

Dashboard Preview
<img width="1291" height="726" alt="Dashboard_screenshot" src="https://github.com/user-attachments/assets/a37cccd2-c874-4969-be86-ba01ccb52a22" />





