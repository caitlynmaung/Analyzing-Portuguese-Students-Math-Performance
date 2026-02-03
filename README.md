1. Introduction
   
    The dataset comes from the UC Irvine Machine Learning Repository. The data contains student characteristics and their academic performance in secondary education for two Portuguese schools. Variables include first/second period grades, age, family size, parents' education levels, parents' occupation, number of absences, number of past failures, etc. Our goal was to determine the variables that had the highest influence on student grades using statistical analysis and machine learning techniques in R.
2.  Key Questions
   
   - How do the first and second-period grades affect the final-period grades?
   - What factors have the greatest influence on the grades that students achieve in secondary education?
   - How do parents’ education level and occupation affect student performance?
3.  Methods Used

   We performed exploratory data analysis using R's lm functions (model building) and statistical packages, such as ggplot and corrplot, to visualize initial trends in the data. In addition, we trained a random forest model on the data to find the numerical variables with the highest importance in predicting grades. Then, we used k-means clustering, an unsupervised machine learning algorithm, to group similar data points together and find underlying patterns between grades, number of failures, and number of absences.

4. Findings

   We discovered that the variables with the most influence on final grades were first and second period grades, number of past failures, number of absences, and intentions to pursue higher education. Other key variables included weekend alcohol consumption, school support, and mother's education and job.
