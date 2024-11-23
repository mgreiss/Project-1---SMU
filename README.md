# Project-1: SMU - Student Performance Analysis
For this project, our group analyzed a dataset focused on student performance factors, sourced from Kaggle. The process began with selecting a dataset of interest, which took longer than expected. Our professor encouraged us to explore multiple datasets before settling on this one, which tracks various factors influencing student performance.

Research Questions:
1. What patterns or relationships exist between specific factors and exam scores (or score differences) across different performance quartiles?
2. Does the gender ratio correlate with the proportion of students earning an 'A', or is one gender more successful than the other despite the ratio?
3. Which factors outside of students' control (e.g., parental involvement, socioeconomic status, access to resources) correlate with their exam scores?
4. How does parental involvement impact students’ general motivation levels?
   
To approach these questions, we divided the work among group members, with each person focusing on one question, while also collaborating on one question together to ensure a collective approach.


Team Responsibilities:

Visualization: The group worked collaboratively to create relevant charts and graphs.
Data Analysis: Each member was responsible for analyzing their specific research question.
PowerPoint Presentation: We collaborated on creating slides to present our findings.


Project Process:

We started by downloading the dataset from Kaggle: Student Performance Factors Dataset.
The necessary Python libraries were integrated from prior class activities:
-pandas
-numpy
-matplotlib
-scipy
-seaborn
-statsmodels

Using these libraries, we imported the data into a Jupyter notebook, created a filepath to read the CSV file, and began analyzing the data.


Analysis Approach:

1. Data Preparation:

We filtered the dataset to focus on students with grades above an "A" for Questions 1 and 2 (i.e., focusing on top performers with scores above 90).
Using code from previous class activities (shared via Slack), we generated a correlation matrix to analyze the relationship between various factors and exam scores.

2. Question 1: Relationship between Exam Scores and Factors:

For the first question, we used in-class techniques and Xpert Learning resources to apply linear regression and explore the correlation between attendance and exam scores among top performers. The results showed a positive correlation.

3. Question 2: Gender and Exam Performance:
   
We used Xpert Learning to analyze the distribution of scores between male and female students, calculating measures such as mean, median, and quartiles (Q1, Q3). A box plot was created to visually display the distribution.
Additionally, we created a pie chart to represent the gender distribution.
To further investigate gender differences, we conducted an ANOVA (also supported by the professor's example in class) to examine the effects of factors like study hours, attendance, and sleep hours on exam performance.

4. Question 3: Factors Outside Students' Control:
   
For question 3, we analyzed how external factors, such as parental involvement, socioeconomic status, and access to resources, affected exam scores. Using ANOVA (informed by in-class activities), we identified significant correlations between these factors and student performance.

5. Question 4: Parental Involvement and Motivation:
   
We used Xpert Learning to create a contingency table to compare parental involvement and student motivation levels. The analysis revealed no strong correlation between the two factors.
To visualize this, we created a pie chart and, after translating categorical data (low, medium, high) into numerical values, we created a comparative bar chart to compare motivation levels at different levels of parental involvement.


Conclusion:

Throughout the project, we divided responsibilities but frequently collaborated to ensure consistency in our analyses and presentation. Our findings provided insight into the relationships between various factors (both within students' control and external) and student performance. Key takeaways include the importance of factors like parental involvement and attendance, as well as gender-based performance differences.


Acknowledgments:

We would like to thank our professor for her guidance throughout this project. Special thanks to Kaggle for providing the dataset and to Xpert Learning for supporting our data analysis.
