# Prediction of water pumps failure 
##  Project Description
The ministry of water of an African country has made a data set of pumps 
installed in various places in the country to serve the water for their countrymen. It is a 
tedious and expensive task to maintain these pumps. This data set contains information 
such as the kind of pump, when it was installed, and how it is managed. We tried to predict 
which pumps require repairs and which are not functional by using the given data set. A 
smart understanding of water point failure can improve maintenance operations and ensure 
that clean and safe water is available to these communities.Implementation of all ML algorithms, data preprocessing and hyperparameters selection were done using inbuilt function from 
scikit learn library in python. All code is present in a single jupyter notebook "code_pumps.ipynb" file and was run on google colab server.


## Data
Training: https://drive.google.com/file/d/1-E-EfSZcREnhyMe23tluDmzNnS2pWSE_/view?usp=sharing

Testing: https://drive.google.com/file/d/1-498FRSmoGj1AqpuPIHU5P8tIwuHEzN1/view?usp=sharing


## Data visulization and exploration
1. It was found that there are certain values missing in the given data. **Multivariate Feature Imputation** is used to estimate these missing values.
2. High correlation between some features were found. Only one of the highly correlated features was kept and others were dropped(**Feature Reduction**)

## Variable transformation, feature engineering, feature selection or elimination
1. Dropped the correlated data
2. converted string to numeric value
3. changed the construction year to numeric value
4. Converted all the Date and time related columns to Date_time objects


## Algorithms used
1. XGB Classifier (giving 78% accuracy)
2. Decision Tree Classifier (giving 74% accuracy)
3. Random forest classifier (giving 80% accuracy)


## Note: 
If you are trying to run the code in your system then make sure all required libraries and data files are present. ALternatively the notebook code.ipynb can be directly
uploaded and run on google colab server without any additional installation.
