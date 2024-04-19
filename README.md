## Welcome to our SC1015 Mini Project : Sleep-Disorder & Stress Analysis Repository
### About
This is a Mini Project for course code SC1015 (Introduction to Data Science and Artificial Intelligence).
Our team's objective is to predict the likelihood of an individual suffering from sleep disorder and high stress levels.
     
### Contributors
The code and slides were done together by all members: Jervis Tham Kai Kit, Yan Jun Chao & Yap Yu Xuan

### Problem Definition
Problem Definition: Finding out the reasons that will explain why people have high stress levels and experience sleep disorders. How do different variables affect the stress level and the likelihood of sleep disorders?

Motivation: Many of our peers are experiencing high levels of stress, while struggling with sleep disorders, and they get overwhelmed without knowing how to reduce it. As students, we are highly exposed to stress and to better manage it, it would be beneficial to know the factors that causes it.

### Variables Chosen from Data Set to be Used
- Sleep Duration (hours): The daily sleep duration of the participant in hours.
- Quality of Sleep (scale: 1-10): A subjective assessment of sleep quality on a scale from 1 to 10.
- Physical Activity Level (minutes/day): The daily duration of physical activity for the participant, measured in minutes.
- BMI Category: The participant's BMI classification (e.g., Underweight, Normal, Overweight).

### Models Used
  1. Logistic Regression
  2. Gradient Boosting
  3. Random Forest 

### Conclusion
- We conclude that using the variables : BMI Category, Sleep Duration and Quality of Sleep, can be used to predict the likelihood of suffering from sleep disorders
- We also conclude that using the variables : Sleep Duration, Quality of Sleep and Level of Physical Health, can be used to predict the likelihood of suffering from high stress levels
- Based on the data, we also observed that these are the optimal values for the variables that we tested:
  BMI Category : Normal
  Quality of Sleep : 7.5 / 10
  Duration of Sleep : > 7.4 hours
  Level of Physical Health : > 75 minutes/day
  
  
### What did we learn from this project?
- Random Forest 
- Logistic Regression 
- Gradient Boosting
- Data Encoding
- Feature Importance
- ROC AUC (Receiver Operating Characteristic Area Under the Curve)

### References
- https://www.kaggle.com/datasets/henryshan/sleep-health-and-lifestyle
