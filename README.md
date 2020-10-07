## Dissertation: Assessing balanced approaches to predict student dropout in Chile
This repository contains the code used for my Dissertation for the MSc Applied Social Data Science at LSE. The data pre-process, including cleaning and creating the final database was done using R. The balancing methods and machine models were created using Python.

## Project Abstract
Student attrition in higher education is a multidimensional problem that carries negative repercussions for individuals, institutions and society. Predictive models focused on identifying students at risk of dropping out can assist institutions in developing interventions to improve retention rates.

Class imbalanced data is an inherent problem in the prediction of attrition that may cause significant loss of performance in classification tasks. Not addressing this problem in the prediction of attrition can lead to overly optimistic results while achieving a poor performance on the classification of the minority class.

This study used data from administrative records available at enrolment to develop models to predict first-year attrition among Chilean students in all institutions of higher education. The models used data from 878,540 undergraduate freshmen students enrolled between 2013 and 2018. Three supervised learning algorithms were compared (Random Forest, XGBoost and Logistic Regression) in unbalanced data and data balanced using eight different resampling techniques to address the problems of imbalanced class distribution.

The results indicated that the data available at the time of enrolment lacked the predictive value to achieve good performance in predictions. Although the balancing techniques did not improve the general performance of the models, all tested methods improved the recall of the minority class while sacrificing some accuracy and precision. Under-sampling techniques showed to be effective methods to clean noisy and borderline examples, and models using Neighbourhood Cleaning Rule and Random Forest as classifying algorithm achieved the best performance.

In addition, an analysis of feature importance was conducted. The possession of scholarships was identified as the variable that contributed the most to the prediction of attrition, underlining the relevance of students’ financial aid. These results suggest that prediction models for attrition, among other variables, should include factors related to the performance of students during their studies in higher education.
