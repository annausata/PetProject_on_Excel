# Project Analysis
## Introduction
Mental health is an increasingly important aspect of overall well-being, yet many individuals struggle to maintain a healthy balance between work, sleep, and physical activity. With this project, I aimed to analyze key factors affecting mental health by leveraging data from a diverse population. By exploring various lifestyle attributes such as sleep hours, work hours, and physical activity, I sought to uncover patterns and insights that can help individuals make informed decisions to improve their mental health and well-being.

### Questions to Analyze 
1. **Who participated in the survey in terms of age groups, countries, and gender distribution?**
2. **How do different age groups compare in terms of work hours, sleep duration, and activity levels?**
3. **What factors contribute to stress levels across different age categories—work hours, sleep duration, or activity time?**
4. **Does the level of stress affect seeking help from a psychologist?**
 

### Excel Skills Used
The following Excel skills were utilized for analysis:
- 📊 Pivot Tables
- 📈 Pivot Charts
- 🧮 DAX (Data Analysis Expressions)
- 🔍 Power Query
- 💪 Power Pivot

### Data Jobs Dataset
This dataset provides a rich collection of anonymized mental health data for 1000 individuals, representing a wide range of ages, genders, occupations, and countries. It aims to shed light on the various factors affecting mental health, offering valuable insights into stress levels, sleep patterns, work-life balance, and physical activity.

## 1️⃣ Who participated in the survey in terms of age groups, countries, and gender distribution?

📥 Extract and Transform  

I first used Power Query to extract the original data (mental_health_dataset.csv).Then, I transformed each query by changing column types, removing unnecessary columns, cleaning text to eliminate specific words.
Additionally, I created a new column to group individuals by age categories, making it easier to analyze different age groups. 

![Applied stepps](https://github.com/user-attachments/assets/0a108d95-bcfe-4d92-80d9-bbf23404c4ae)

After transforming the data, I designed a dashboard to visualize the survey participants, including their age groups, countries, and gender distribution.
 
![Getting to know the data](https://github.com/user-attachments/assets/ab8d44c9-b503-4d6a-bcb7-fbe8e86a089d)

### 🤔 Insights and Recommendations
This Excel sheet provides an overview of the dataset, allowing users to explore key demographic information. It presents the distribution of individuals across different age categories, ranging from Young (18-25) to Senior (56-65). The data also showcases the geographical representation of participants from various countries, including Australia, India, the USA, Germany, the UK, Canada, and others. Additionally, the charts offer insights into the gender distribution, covering Female, Male, Non-binary, and individuals who prefer not to disclose their gender. This visual representation helps in understanding the diversity within the dataset. 

## 2️⃣ How do different age groups compare in terms of work hours, sleep duration, and activity levels?

📊 Analysis of Age Groups in Terms of Work Hours, Sleep Duration, and Activity Levels

To explore how different age groups compare in terms of work hours, sleep duration, and activity levels, I created a dashboard that presents the data visually.

1. The first chart, titled *"Average Lifestyle Metrics by Age Group"* provides a comparative overview of the number of hours dedicated to sleep, work, and physical activities across four age categories: Young, Middle-aged, Mature, and Senior. This visualization helps identify trends and differences in lifestyle habits.  

2. The second chart, *"Occupational Trends Across Age Categories"* shows the distribution of occupations among different age groups, offering insights into the professional background of the respondents.
These visualizations allow us to analyze patterns and understand how lifestyle factors vary with age.

![Lyfestyle Factors](https://github.com/user-attachments/assets/0034c994-5157-4f0e-8733-6077d3db7d7a)

📊 Key Observations from the First Chart

From the first chart, it is evident that:

- Sleep duration and activity levels remain relatively consistent across all age groups, showing minimal variation.
- However, working hours reach their peak in the 41-55 age group (Mature category), indicating that individuals in this age range tend to have the highest workload compared to other groups.

**This insight suggests that midlife might be the most demanding period in terms of professional commitments.**

📊 Utilizing Filters for Deeper Analysis

At the bottom of the dashboard, various filters are available to refine the analysis. For this specific study, the gender filter can be applied to gain additional insights.  
An interesting observation emerges when using the gender filter:

- Women tend to have the lowest number of working hours during their youth.  
![Average Lifestyle Metrics for females](https://github.com/user-attachments/assets/c97680be-140c-410f-8425-ef63a4b41b7d)

- Men, on the other hand, work the most during the same period.  
![Average Lifestyle Metrics for males](https://github.com/user-attachments/assets/ed431f45-27ba-4170-9969-19560dad3b75)

**These insights help us better understand how work-life balance differs between genders across different age groups.**

Additionally, the occupation filter can be used to perform a more precise analysis, allowing us to examine how different professions influence sleep patterns, work hours, and activity levels across various occupations.

### 🤔 Insights and Recommendations
These insights suggest that work-life balance varies significantly by gender and age group. Women may prioritize other aspects of life during their youth, while men tend to focus more on work. The peak in working hours for middle-aged individuals highlights career demands during this phase. Analyzing professions further can provide deeper insights into lifestyle differences across various fields.

## 3️⃣ What factors contribute to stress levels across different age categories—work hours, sleep duration, or activity time?

📊 Factors Contributing to Stress Levels Across Different Age Categories

Using the previously analyzed dashboard, we can observe the following key insights regarding stress levels:

On the left is the chart for **low** stress levels, and on the right is the chart for **high** stress levels.    
![Stress Level](https://github.com/user-attachments/assets/a9b929c2-59e4-45fd-817f-10da5d5ae96f)


**Impact of Sleep Duration:**
- Sleep duration does **not** have a significant influence on stress levels.
- Other factors, such as physical activity and work hours, play a more critical role.

**Role of Physical Activity:**
- Across all age categories, **higher physical activity** correlates with **lower stress levels**.   
*Conclusion:* Engaging in regular physical activities helps in managing stress effectively.

**Influence of Work Hours:**  
The effect of work hours on stress varies across different age groups:

Young, Senior, and Mature individuals:
- Tend to experience higher stress when working fewer hours.    
*Possible reasons:* Lack of purpose, financial insecurity, and underutilization of potential.

Middle-aged individuals:
- Experience higher stress with longer working hours.    
*Possible reasons:* Increased career responsibilities, family commitments, and work-life balance challenges.

**These insights suggest that managing physical activity and work hours effectively can significantly impact stress levels across different age groups.**

### 🤔 Insights and Recommendations
To reduce stress levels, all age groups should prioritize increasing their physical activity, as it plays a key role in lowering stress. Additionally, Young, Senior, and Mature individuals may benefit from balancing their work hours, as lower working hours are associated with higher stress levels in these groups. In contrast, Middle-aged individuals should focus on maintaining a manageable workload, as higher work hours seem to correlate with lower stress levels for them.

## 4️⃣ Does the level of stress affect seeking help from a psychologist?

📊 The Relationship Between Stress Levels and Seeking Psychological Help  

This is the main dashboard we will use for the next question. On the left, we can see a chart indicating stress levels across different age categories. On the right, there is a chart showing how, on average, each age group seeks psychological help. In the center, various filters are available for deeper analysis.  

![Stress Level VS Consultation](https://github.com/user-attachments/assets/99ab5f2c-5a1d-4de2-af4c-4c19c2e67afa)  

We will use the consultation chart for analysis. From the overall statistics, we can already see that, across all age groups, the data is roughly split evenly between those who have consulted a psychologist and those who have not.   

**But what happens if we filter for individuals with higher stress levels or those with lower stress levels?**  

![Consultation between low and high stress level](https://github.com/user-attachments/assets/0c4305bd-8075-47a6-a802-0f84c24dfad8)  

Analyzing the data, it becomes evident that the level of stress does not significantly influence whether individuals seek professional psychological help. Across all stress levels (low, medium, high), the proportion of people who consult psychologists versus those who don’t remains almost evenly split.  

This finding is surprising, especially for individuals with high stress levels, where one might expect a higher tendency to seek professional support. However, the statistics reveal that even among highly stressed individuals, the percentage of those who reach out to psychologists does not significantly increase.  

Possible Explanations:
1. **Stigma Around Mental Health:** many individuals, regardless of stress level, may hesitate to seek help due to the stigma associated with mental health issues.
2. **Limited Access to Resources:** even highly stressed individuals might not consult a psychologist due to financial constraints, lack of access to professionals, or unawareness of available resources.
3. **Coping Mechanisms:** some people may rely on personal coping mechanisms, such as support from friends or family, rather than seeking professional help, even when experiencing high stress.
4. **Underestimation of Stress Impact:** many individuals might not recognize the severity of their stress or associate it with the need for professional intervention, leading to similar consultation rates across all stress levels.

### 🤔 Insights and Recommendations
These findings highlight the need to address barriers to accessing psychological help, increase awareness about mental health, and promote the importance of seeking professional support, especially for individuals experiencing high levels of stress.

## Conclusion
### Excel Skills Used

Throughout this analysis, I applied the following Excel skills:

📊 Pivot Tables: Used to create summarized data tables, which were later transformed into Pivot Charts for visualization.  
📈 Pivot Charts: Created from Pivot Tables to visualize the data and identify trends across different categories.  
🔍 Power Query: Utilized for data transformation and cleaning to ensure the dataset was structured and ready for analysis.  
🧮 DAX (Data Analysis Expressions): Used to write formulas for creating new calculated columns and measures to enhance the analysis.    
💪 Power Pivot: Applied to refine the data model, making it more efficient and enabling easier calculation of key metrics.

These tools and techniques allowed me to perform a comprehensive analysis, from data preparation to visualization, ensuring meaningful insights.  

As someone passionate about data analysis, I undertook this Excel-based project to explore stress levels across different age groups and their relationship to seeking professional psychological help. Using a comprehensive dataset, I analyzed stress levels, categorized age groups, and examined consultation rates with psychologists.  

This project not only deepened my understanding of Excel's advanced capabilities but also provided a clearer perspective on how stress impacts individuals' decisions to seek professional help. I hope this work highlights the importance of mental health support and showcases the power of data-driven analysis.
