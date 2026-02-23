# Mental Health in Tech - Exploratory Data Analysis

**Date:** February 2026

## Overview
Analyzed the **OSMI** Mental Health in Tech dataset to identify key factors influencing mental health in the tech workspace and understand its impact on work and well-being.

**Tools & Technologies:** Python (Pands, Numpy, Seaborn, Matplotlib), Jupyter Notebook

**Dataset:** [Kaggle Mental Health in the Tech Workplace](https://www.kaggle.com/osmi/mental-health-in-tech-survey)

**Context**
This dataset is from a 2014 survey that measures attitudes towards mental health and frequency of mental health disorders in the tech workplace.

**Data Dictionary**
1. ***Timestamp:*** Date and time of survey response
2. ***Age:*** Age of the respondent
3. ***Gender:*** Gender of the respondent
4. ***Country:*** Country of residence
5. ***State:*** If in the US, which state or territory
6. ***Self_employed:*** Are you self-employed?
7. ***Family_history:*** Do you have a family history of mental illness?
8. ***Treatment:*** Have you sought treatment for a mental health condition?
9. ***Work_interfere:*** Does your mental health condition interfere with your work?
10. ***No_employees:*** Number of employees in your company
11. ***Remote_work:*** Do you work remotely at least 50% of the time?
12. ***Tech_company:*** Is your employer primarily a tech company?
13. ***Benefits:*** Does your employer provide mental health benefits?
14. ***Care_options:*** Do you know the mental health care options your employer provides?
15. ***Wellness_program:*** Has your employer discussed mental health as part of a wellness program?
16. ***Seek_help:*** Does your employer provide resources to learn more about mental health?
17. ***Anonymity:*** Is your anonymity protected if you use mental health treatment resources?
18. ***Leave:*** How easy is it to take medical leave for a mental health condition?
19. ***Mentalhealthconsequence:*** Would discussing mental health with your employer have negative consequences?
20. ***Physhealthconsequence:*** Would discussing physical health with your employer have negative consequences?
21. ***Coworkers:*** Would you discuss a mental health issue with your coworkers?
22. ***Supervisor:*** Would you discuss a mental health issue with your supervisor?
23. ***Mentalhealthinterview:*** Would you bring up mental health with a potential employer in an interview?
24. ***Physhealthinterview:*** Would you bring up physical health with a potential employer in an interview?
25. ***Mentalvsphysical:*** Does your employer take mental health as seriously as physical health?
26. ***Obs_consequence:*** Have you observed negative consequences for coworkers with mental health conditions?
27. ***Comments:*** Any additional notes or comments

**Key Questions**
1. Which **age group** is most conscious about mental health?
2. Does **gender** influence seeking treatment?
3. Does **family history** influence seeking treatment?
4. Does **work interference** affect treatment?
5. Which **company sizes** have more mental health issues?
6. Which **countries** contribute most?

---

## Key Findings

 1. Age vs Treatment - Ages 18-34 are highest in number seeking treatment vs other groups, but percentages within each (taking vs not) are nearly same (around 50%), except 55-65 group where almost 68% seek it.
 2. Gender vs Treatment - In females, more than 68% seek treatment, whereas in males it's slightly above half (54%), and 79% in the other group.
 3. Family History vs Treatment - People with family history of mental health issues seek treatment at much higher rates.
 4. Work Interference vs Treatment - Work interference shows more even distribution, with most reporting "sometimes."
 5. Company Size vs Treatment - The proportion seeking treatment stays relatively consistent above 0.4 regardless of company size.
 6. Top 10 Countries - USA leads the list with a huge gap over the next countries, followed by UK and Canada.

 ---

 Notebook - [`mental-health-in-tech-analysis.ipynb`](mental-health-in-tech-analysis.ipynb) - Complete analysis (cleaning, viz, correlations)
