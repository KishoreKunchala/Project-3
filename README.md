# Project-3
Salary Prediction with Machine Learning

For salary prediction, we need to find relationships in the data on how the salary is determined. For this task, we need to have a dataset based on salaries. I found a dataset that contains data about how job experience affects salary.

The dataset contains two columns only:

job experience
salary

Loaded the dataset,checked wether it has any null values,plotted scatterplot to find the relationship between salary and experience.There is a perfect linear relationship between the salary and the job experience of the people. It means more job experience results in a higher salary.

As this is a regression analysis problem,trained a regression model to predict salary with Machine Learning.Before that divided the data into train and test sets.Used LinearRegression model and trained that model.Then predicted the salary of a person using the trained Machine Learning model.

Python Libraries used:Numpy,Pandas,Seaborn
Machine Learning model:LinearRegression.
