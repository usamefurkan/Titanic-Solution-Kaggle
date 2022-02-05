# Titanic Solution - Kaggle

## Overview
The project aims to predict which passengers on the Titanic are more likely to survive. Predictions were made using classification algorithms (machine learning) and tensorflow (deep learning). 

## Implementation details
* As a result of the models trained in project, it was aimed to have score above 0.40 at Kaggle
* Explororaty data analysis, data visualizaton and feature engineering have been done to achieve the goal.
* Firstly, exploratory data analysis was performed. Examined how data affects house prices. Null values specified. The number of people in the family was inferred, as passengers would be more likely to die trying to save their families.  
* Titles were founded from passenger names  Nulls in the age column were filled with either the median of each title
* Categorical variables were converted into dummy/indicator variables.
* Training was conducted using 7 different classification models. Accuracy, precision, recall and f1 score results of each model are listed as a table.  The most efficient estimations was obtained in the Decision Tree algorithm.
* Predictions obtained using machine learning are written to csv file by creating a new dataframe When I submitted the .csv file to the titanic contest on Kaggle, I got a score of 0.74
* Prediction was also done using tensorflow. binary_crossentropy was used as loss function. epochs=450, batch size=10.
* Predictions obtained using deep learning are written to csv file by creating a new dataframe. When I submitted the .csv file to the titanic contest on Kaggle, I got a score of 0.77







