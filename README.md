# Credit_Risk_Analysis
# MEMORANDUM

# To: Credit Department
# From: Bob
# Re: Machine-Learning Models for Credit Card Risk Assessment

# Overview of Project
## We evaluated six different modifications for our Logistic Regression machine learning model to identify the best available method for predicting the riskiness of potential loans. Since our finance group determined that high-risk loans which were incorrectly classified as low-risk loans proposes the greatest threat to our business, we recommend the use of Easy Ensemble AdaBoost Classifier due its high accuracy as well as superior sensitivity. 
#
# Results
## Methodology – The data received from the Marketing Department required some pre-processing before our analysis began. In addition to deleting empty rows and columns, we eliminated nine additional columns since all values in those columns were identical. We also simplified two columns (home_ownership and verification_status) and limited values to one of two choices. 
##
## Values - The following table provides the accuracy of each method as well as the precision and sensitivity (recall) for high risk loans:
Model Modification	Accuracy	Precision	Sensitivity
Naïve Random Oversampling	0.652	0.01	0.72
SMOTE Oversampling	0.656	0.01	0.64
Cluster Centroid Undersampling	0.549	0.01	0.69
SMOTEENN	0.645	0.01	0.72
Balanced Forest Random Classifier	0.763	0.03	0.65
Easy Ensemble AdaBoost Classifier	0.932	0.09	0.92
##
#
# Summary
## Since this work centered on only three months of data and included limited refinement efforts, we recommend the creation of a project team to develop a new model which employs the Easy Ensemble AdaBoost Classifier to analyze a larger data set and then undertake an organized effort to refine the model parameters.
