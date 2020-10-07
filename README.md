# Dissertation: Assessing balanced approaches to predict student dropout

## Description
This repository contains the code used for my Dissertation for the MSc Applied Social Data Science at LSE. The data pre-process, including cleaning and creating the final database was done using R. The balancing methods and machine models were created using Python.

## The Project
The main goal of this project was to develop models to identify first-year students at risk of dropping out of Technical Training Centres, Professional Institutes and Universities in Chile, using administrative information available from official records.

### Research Questions
1. What classifying algorithm provides the best performance identifying first-year dropout students in higher education in Chile?
2. What resampling technique is most effective in addressing the problems of imbalanced data for the prediction of student attrition in higher education in Chile?
3. What are the factors that contribute the most to predict the probability of student dropout out during the first year of higher education in Chile?

### Abstract
Student attrition in higher education is a multidimensional problem that carries negative repercussions for individuals, institutions and society. Predictive models focused on identifying students at risk of dropping out can assist institutions in developing interventions to improve retention rates.

Class imbalanced data is an inherent problem in the prediction of attrition that may cause significant loss of performance in classification tasks. Not addressing this problem in the prediction of attrition can lead to overly optimistic results while achieving a poor performance on the classification of the minority class.

This study used data from administrative records available at enrolment to develop models to predict first-year attrition among Chilean students in all institutions of higher education. The models used data from 878,540 undergraduate freshmen students enrolled between 2013 and 2018. Three supervised learning algorithms were compared (Random Forest, XGBoost and Logistic Regression) in unbalanced data and data balanced using eight different resampling techniques to address the problems of imbalanced class distribution.

The results indicated that the data available at the time of enrolment lacked the predictive value to achieve good performance in predictions. Although the balancing techniques did not improve the general performance of the models, all tested methods improved the recall of the minority class while sacrificing some accuracy and precision. Under-sampling techniques showed to be effective methods to clean noisy and borderline examples, and models using Neighbourhood Cleaning Rule and Random Forest as classifying algorithm achieved the best performance.

In addition, an analysis of feature importance was conducted. The possession of scholarships was identified as the variable that contributed the most to the prediction of attrition, underlining the relevance of students’ financial aid. These results suggest that prediction models for attrition, among other variables, should include factors related to the performance of students during their studies in higher education.

### Data Sources
This study used administrative data from the Chilean government agencies that compose the System of Quality Assurance in Education, which includes the Ministry of Education of Chile (MINEDUC), the National Education Council of Chile (CNED) and the Educational Quality Agency. The databases used are made openly available through an [open data platform](http://datosabiertos.mineduc.cl) created by the Ministry of Education.
