# human_activity_recognition_using_smartphone
machine learning 
Description of experiment
The experiments have been carried out with a group of 30 volunteers within an age bracket of 19-48 years. Each person performed six activities (WALKING, WALKINGUPSTAIRS, WALKINGDOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the waist. Using its embedded accelerometer and gyroscope, we captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz. The experiments have been video-recorded to label the data manually. The obtained dataset has been randomly partitioned into two sets, where 70% of the volunteers was selected for generating the training data and 30% the test data.

The sensor signals (accelerometer and gyroscope) were pre-processed by applying noise filters and then sampled in fixed-width sliding windows of 2.56 sec and 50% overlap (128 readings/window). The sensor acceleration signal, which has gravitational and body motion components, was separated using a Butterworth low-pass filter into body acceleration and gravity. The gravitational force is assumed to have only low frequency components, therefore a filter with 0.3 Hz cutoff frequency was used. From each window, a vector of features was obtained by calculating variables from the time and frequency domain.

Notebook - Table of Content
Importing necessary libraries
Loading data
Data preprocessing
3.a Checking for duplicates
3.b Checking for missing values
3.c Checking for class imbalance
Exploratory Data Analysis
4.a Analysing tBodyAccMag-mean feature
4.b Analysing Angle between X-axis and gravityMean feature
4.c Analysing Angle between Y-axis and gravityMean feature
4.d Visualizing data using t-SNE
Model Prediction and Evaluation
5.a Logistic regression model with Hyperparameter tuning and cross validation
5.b Linear SVM model with Hyperparameter tuning and cross validation
5.c Kernel SVM model with Hyperparameter tuning and cross validation
5.d Decision tree model with Hyperparameter tuning and cross validation
5.e Random forest model with Hyperparameter tuning and cross validation
