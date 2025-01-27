# Project Analysis
## Introduction
Mental health is an increasingly important aspect of overall well-being, yet many individuals struggle to maintain a healthy balance between work, sleep, and physical activity. With this project, I aimed to analyze key factors affecting mental health by leveraging data from a diverse population. By exploring various lifestyle attributes such as sleep hours, work hours, and physical activity, I sought to uncover patterns and insights that can help individuals make informed decisions to improve their mental health and well-being.

### Questions to Analyze 
1. **Who participated in the survey in terms of age groups, countries, and gender distribution?**
2. **How do different age groups compare in terms of work hours, sleep duration, and activity levels?**
3. **What factors contribute to stress levels across different age categories—work hours, sleep duration, or activity time?**
4. **Does stress level affect seeking help from a psychologist?**
 

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

### 🤔So What
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
![Avarage Lifestyle Metrics for female (1)](https://github.com/user-attachments/assets/c97680be-140c-410f-8425-ef63a4b41b7d)

- Men, on the other hand, work the most during the same period.  
![Avarage Lifestyle Metrics for male](https://github.com/user-attachments/assets/ed431f45-27ba-4170-9969-19560dad3b75)

**These insights help us better understand how work-life balance differs between genders across different age groups.**

Additionally, the occupation filter can be used to perform a more precise analysis, allowing us to examine how different professions influence sleep patterns, work hours, and activity levels across various occupations.

### 🤔 So What
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

### 🤔 So What
To reduce stress levels, all age groups should prioritize increasing their physical activity, as it plays a key role in lowering stress. Additionally, Young, Senior, and Mature individuals may benefit from balancing their work hours, as lower working hours are associated with higher stress levels in these groups. In contrast, Middle-aged individuals should focus on maintaining a manageable workload, as higher work hours seem to correlate with lower stress levels for them.

## 4️⃣ Does stress level affect seeking help from a psychologist?
