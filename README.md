<h2>Wine Quality Prediction</h2>
<h5>Introduction</h5>


The Wine Quality Prediction aims to analyze and predict the quality of white variants of the wine based on physicochemical attributes. The dataset provides valuable insights into the chemical composition of wines and how these attributes influence the perceived quality.


Here is the CoLab link for the case study
https://colab.research.google.com/drive/1wIuuxox9-lA3wb9bFlP4PWsPnoH5LhBi?usp=sharing



Dataset

The dataset consists of the following attributes:

    Input Variables (based on physicochemical tests):
        Fixed acidity
        Volatile acidity
        Citric acid
        Residual sugar
        Chlorides
        Free sulfur dioxide
        Total sulfur dioxide
        Density
        pH
        Sulphates
        Alcohol
        Type

    Output Variable (based on sensory data):
        Quality (score between 0 and 10)

The project involves building classification models to predict wine quality based on these attributes. The dataset presents a challenging task due to its imbalanced and relatively small sample size.


In the dataset, each column represents a specific attribute related to wine quality. The values in these columns have no missing data, with no null values present (0 missing values) in any of the attributes. This clean dataset is ready for analysis and modeling.

Due to the absence of missing data in the dataset's attributes, we have skipped the following steps:


    Data Imputation: There was no need to fill or impute missing values since all columns are complete, saving time and complexity in data preprocessing.
    
    Missing Data Analysis: The step of analyzing patterns or causes of missing data was unnecessary, as the dataset was devoid of any missing values.

    Handling Missing Values: With no null values to address, there was no requirement for strategies such as imputation, removal of incomplete rows, or advanced techniques to manage missing data.

Here i have performed 4 model on this data set. 
1. Logistic Regression
2. DecisionTree Classifier
3. SVC
4. RandomForest Classifier

![image](https://github.com/mesba-islam/WineQualityPrediction/assets/82472635/b4922d90-8742-4c26-8255-543797759e03)


after evaluating several regression models on the Wine Quality dataset, i have determined the best model is Random Forest Classifier.
