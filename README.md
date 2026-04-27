# International Students’ Mental Health by Length of Stay (1–10 Years)


## Project Overview
This project explores and analyzes international students' mental health data to understand how the length of stay impacts average mental health diagnostic scores.

The analysis focuses on international students only and analyzes the average scores of:
- PHQ-9 depression test
- SCS social connectedness test
- ASISS acculturative stress test


## Dataset
The dataset contains student information such as student type, language proficiency, academic level, age, length of stay, and mental health diagnostic scores.


## Tools Used
- SQL
- Power BI
- CSV


## SQL Analysis
The CSV data was analyzed using SQL. The query grouped international students by their length of stay and calculated:
- Number of international students
- Average PHQ-9 score
- Average SCS score
- Average ASISS score


## Mental Health Scores Explanation
- **Average PHQ-9 Score**:  
  The average depression score for international students.  
  PHQ-9 is used to measure the level of depression symptoms.  
  A higher PHQ-9 score indicates a higher level of depression symptoms.

- **Average SCS Score**:  
  The average social connectedness score for international students.  
  SCS measures how socially connected students feel.  
  A higher SCS score indicates stronger social connectedness.

- **Average ASISS Score**:  
  The average acculturative stress score for international students.  
  ASISS measures stress related to adapting to a new culture or environment.  
  A higher ASISS score indicates higher acculturative stress.


## Power BI Dashboard
The SQL results were exported as a CSV file and used in Power BI to create visual charts showing the relationship between length of stay and mental health scores.


## Dashboard Preview
![Dashboard Preview](04_powerbi/International%20Students%20Mental%20Health%20Screenshot.png)


## Project Files
- `01_data/Students_Data.csv`: Original dataset
- `02_sql/02.1 Task Description.txt`: Task requirements
- `02_sql/02.2 Mental Health by Stay Analysis.sql`: SQL query used for analysis
- `03_results/Mental Health by Stay Results.csv`: SQL query result
- `04_powerbi/International Students Mental Health Dashboard.pbix`: Power BI dashboard file
- `04_powerbi/International Students Mental Health Screenshot.png`: Dashboard screenshot


## Key Insights
- The analysis is based on 201 international students.
- Depression scores vary across different lengths of stay, with noticeable changes between 5 and 10 years.
- Social connectedness reaches its highest average around 7 years of stay.
- Acculturative stress appears highest around 5 years of stay, then drops noticeably around 7 years.
- Some stay groups have fewer students, so their average scores should be interpreted carefully.