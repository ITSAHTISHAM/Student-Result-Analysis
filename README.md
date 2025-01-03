# Student Result Analysis

## Overview

This project focuses on analyzing student performance data to identify trends and insights. The dataset contains information on various student attributes, their family backgrounds, and their academic scores in Math, Reading, and Writing. Through data visualization and statistical analysis, this project explores relationships between the students' attributes and their academic outcomes.

## Dataset

The dataset used in this project is titled `Expanded_data_with_more_features.csv`. It contains 30641 records and 15 columns, each representing a specific attribute or score related to the students.

### Key Features:

- `Gender`: Gender of the student.
- `EthnicGroup`: Ethnic group of the student.
- `ParentEduc`: Education level of the parent.
- `LunchType`: Type of lunch received by the student.
- `TestPrep`: Whether the student has completed test preparation.
- `ParentMaritalStatus`: Marital status of the parent.
- `PracticeSport`: Frequency of sports practice.
- `IsFirstChild`: Whether the student is the first child in the family.
- `NrSiblings`: Number of siblings.
- `TransportMeans`: Mode of transportation to school.
- `WklyStudyHours`: Weekly study hours.
- `MathScore`: Math test score.
- `ReadingScore`: Reading test score.
- `WritingScore`: Writing test score.

## Project Visuals

![Screenshot (16)](https://github.com/user-attachments/assets/ee1eaaa4-862f-4b28-b4f3-74fa09642caf)
![Screenshot (17)](https://github.com/user-attachments/assets/41fb3a71-acc3-4772-8896-ef3d5b53077c)
![Screenshot (18)](https://github.com/user-attachments/assets/f747532e-f691-4b7d-9dba-945c9735d03a)
![Screenshot (19)](https://github.com/user-attachments/assets/ac19cb41-3cc7-4f01-8d08-61114d51e43e)
![Screenshot (20)](https://github.com/user-attachments/assets/707ec840-ef99-4c10-91ed-d9427069fded)

## Data Cleaning:

- The `Unnamed: 0` column was dropped as it served no analytical purpose.
- Missing values in the dataset were identified and handled during analysis.

## Analysis and Insights

### Gender Distribution

- A bar chart visualized the gender distribution, revealing that there are more females than males in the dataset.

### Parent Education vs. Student Scores

- Grouped data by `ParentEduc` and calculated the mean scores for Math, Reading, and Writing.
- A heatmap indicated that higher parent education levels positively correlate with student scores.

### Parent Marital Status vs. Student Scores

- Grouped data by `ParentMaritalStatus` and calculated the mean scores for Math, Reading, and Writing.
- A heatmap showed negligible impact of parental marital status on student scores.

### Score Distributions

- Box plots for `MathScore`, `ReadingScore`, and `WritingScore` displayed the distribution and outliers in the scores.

### Ethnic Group Distribution

- A pie chart and a bar chart visualized the distribution of students across different ethnic groups.

## Code Highlights

### Data Exploration:

- `df.describe()` and `df.info()` provided an overview of data types, missing values, and statistical summaries.
- `df.isnull().sum()` helped identify the extent of missing data in each column.

### Visualizations:

- Bar and pie charts to analyze categorical data distributions.
- Heatmaps to identify relationships between variables.
- Box plots to analyze score distributions.

### Grouping and Aggregations:

- Used `groupby` to calculate mean scores based on categorical features like `ParentEduc` and `ParentMaritalStatus`.

## Tools and Libraries

- **Python**: Programming language used for data analysis.

### Libraries:

- `numpy` and `pandas` for data manipulation.
- `matplotlib` and `seaborn` for data visualization.

## Conclusion

The analysis revealed several key insights:

- Students' scores are positively influenced by higher levels of parental education.
- Gender and ethnic group distributions provide an understanding of the dataset’s demographics.
- Parental marital status has little to no impact on academic performance.

This project demonstrates how data analysis techniques can uncover meaningful patterns in educational datasets. Future work could include predictive modeling or deeper exploration of other factors influencing student performance.

