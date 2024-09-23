# HR Analytics

## Overview

This report seeks to deliver comprehensive insights into two critical facets of human resource management: employee attrition and training program effectiveness. The analysis leverages a robust dataset encompassing various HR metrics, including but not limited to age, department, performance ratings, tenure, and job satisfaction levels. By examining these dimensions, the report aims to uncover patterns and correlations that can inform strategic HR decisions and improve overall organizational performance.

## Objectives
The project is centered around two primary objectives:

1.	**Identify Factors Influencing Employee Attrition**:
To pinpoint the key factors contributing to employee attrition and provide actionable insights aimed at reducing attrition rates. This involves analyzing variables such as job satisfaction, work-life balance, compensation, career development opportunities, and organizational culture.

2.	**Evaluate Training Program Effectiveness**:
To assess the effectiveness of current training programs and recommend targeted improvements. This includes examining metrics like employee performance post-training, skill acquisition, training satisfaction, and the impact on overall productivity and employee engagement.

## Data Cleaning and Preparation
The initial dataset contained several missing values and discrepancies. Data cleaning involved:

1. For the Gender & Position column, the values were updated to a more concise format for easier handling in future analyses. Specifically, the transformations were:

     - 'Female' was replaced with 'F'
     - 'Male' was replaced with 'M
     - 'DataScientist' was replaced with 'Data Scientist'
    - 'Marketinganalyst' was replaced with 'Marketing Analyst'

2. For the purpose of more detailed analysis, the Age and Salary columns were categorized into different groups. These categorizations were designed to facilitate subgroup analyses, enabling the
identification of patterns or trends that might not be obvious when considering the entire data set.

      - Age Categories: <br>
              i. Less than or equal to 30 years <br>
             ii. Greater than 30 years <br>
    
      - Salary Categories <br>
              i. 50K - 60K <br>
             ii. 60K - 70K <br>
            iii. 70K - 80K <br>
             iv. 80K - 90K <br>
              v. 90K - 100K <br>

3. Converting the Last Promotion Date to a standard date format.

## Analysis and Insights

### 1. Department Wise Attrition

   #### Observations

  ![Alt text](https://pasteboard.co/T7uLA5lCNO2V.png)


 - The Sales department has the highest attrition rate, followed closely by the HR department.<br>
 - The Operations department experiences the lowest attrition rate. <br>
 - The Finance department, despite having a substantial number of employees, also faces a significant attrition rate. <br>


  #### Possible Reasons behind attrition
   
   
   (i) **Sales Department**:<br>
    - High Attrition Rate: Sales roles often come with high-pressure targets and performance expectations, which can lead to burnout and turnover. Additionally, sales positions may offer more opportunities 
      elsewhere, prompting employees to switch jobs frequently.

  (ii) **HR Department**: <br>
    - High Attrition Rate: HR professionals might experience high turnover due to the demanding nature of their roles, which often involve managing employee relations, recruitment, and compliance. The stress 
      associated with these responsibilities can contribute to higher attrition.

  (iii) **Operations Department**: <br>
    - Low Attrition Rate: Operations roles typically involve more stable and routine tasks, which might lead to higher job satisfaction and lower turnover. Employees in operations may also have fewer external job 
      opportunities compared to sales or HR.

  (iv) **Finance Department**: <br>
    - Significant Attrition Rate: Despite having a large workforce, the Finance department faces notable attrition. This could be due to the high-stress environment, long working hours, and the critical nature of 
     financial tasks. Additionally, finance professionals often have transferable skills that are in demand, making it easier for them to find new opportunities

### 2. Position Wise Attrition

![alt_text][image](https://github.com/user-attachments/assets/1372415e-331d-4ea5-8b53-e3954524e7f1)


