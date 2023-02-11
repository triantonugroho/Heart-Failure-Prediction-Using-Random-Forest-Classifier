## Heart Failure Prediction Using Random Forest Classifier ##

* ### This project predicts whether a person has heart disease or not using a Random Forest Classifier model that uses  Hyperparameters Tuning with GridSearchCV to get the best model performance with an Accuracy of 87,68 %, Precision 90,32 %, Recall 88,05 %, and ROC AUC 87,61%.

![1](https://user-images.githubusercontent.com/91950433/218257294-4f2de0ff-c859-4239-a7fe-fd04c4c86fc8.png)

![2](https://user-images.githubusercontent.com/91950433/218258656-2d2a814e-527c-470a-ad21-d7304ff20b92.png)

![3](https://user-images.githubusercontent.com/91950433/218258665-bac6440d-4481-41ea-8852-edde996b571f.png)

* ### This project predicts whether a person has heart disease or not using a Random Forest Classifier model that uses  Hyperparameters Tuning with GridSearchCV to get the best model performance with an Accuracy of 87,68 %, Precision 90,32 %, Recall 88,05 %, and ROC AUC 87,61%.

### Data Understanding ###

* #### Context

Cardiovascular diseases (CVDs) are the number 1 cause of death globally, taking an estimated 17.9 million lives each year, which accounts for 31% of all deaths worldwide. Four out of 5CVD deaths are due to heart attacks and strokes, and one-third of these deaths occur prematurely in people under 70 years of age. Heart failure is a common event caused by CVDs and this dataset contains 11 features that can be used to predict a possible heart disease.

People with cardiovascular disease or who are at high cardiovascular risk (due to the presence of one or more risk factors such as hypertension, diabetes, hyperlipidaemia or already established disease) need early detection and management wherein a machine learning model can be of great help.

* #### Attribute Information
1. **Age**: age of the patient [years]
2. **Sex**: sex of the patient [M: Male, F: Female]
3. **ChestPainType**: chest pain type [TA: Typical Angina, ATA: Atypical Angina, NAP: Non-Anginal Pain, ASY: Asymptomatic]
4. **RestingBP**: resting blood pressure [mm Hg]
5. **Cholesterol**: serum cholesterol [mm/dl]
6. **FastingBS**: fasting blood sugar [1: if FastingBS > 120 mg/dl, 0: otherwise]
7. **RestingECG**: resting electrocardiogram results [Normal: Normal, ST: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV), LVH: showing probable or definite left ventricular hypertrophy by Estes' criteria]
8. **MaxHR**: maximum heart rate achieved [Numeric value between 60 and 202]
9. **ExerciseAngina**: exercise-induced angina [Y: Yes, N: No]
10. **Oldpeak**: oldpeak = ST [Numeric value measured in depression]
11. **ST_Slope**: the slope of the peak exercise ST segment [Up: upsloping, Flat: flat, Down: downsloping]
12. **HeartDisease**: output class [1: heart disease, 0: Normal]

* #### Source
This dataset was created by combining different datasets already available independently but not combined before. In this dataset, 5 heart datasets are combined over 11 common features which makes it the largest heart disease dataset available so far for research purposes. The five datasets used for its curation are:

Cleveland: 303 observations
Hungarian: 294 observations
Switzerland: 123 observations
Long Beach VA: 200 observations
Stalog (Heart) Data Set: 270 observations
Total: 1190 observations
Duplicated: 272 observations

Final dataset: 918 observations

Every dataset used can be found under the Index of heart disease datasets from UCI Machine Learning Repository on the following link: https://archive.ics.uci.edu/ml/machine-learning-databases/heart-disease/ 

* #### Citation
fedesoriano. (September 2021). Heart Failure Prediction Dataset. Retrieved [Date Retrieved] from https://www.kaggle.com/fedesoriano/heart-failure-prediction.

* #### Dimension
The data contains 918 bars and 12 columns.

### Exploratory Data Analysis

* #### Import Library

* #### Upload Dataset

* #### Read Dataset

* #### Display 5 Samples

* #### Dataset Information

* #### Checking Shape

* #### Checking Missing Value

* #### Checking Data Duplicate

* #### Checking Label Proportion

* #### Descriptive Statistics

* #### Histogram

* #### Pair Plot

* #### Correlation

* #### Checking for Multicollinearity

* #### Data Exploration

  - Age
  - Sex
  - ChestPainType
  - RestingBP
  - Cholesterol
  - FastingBS
  - RestingECG
  - MaxHR
  - ExerciseAngina
  - Oldpeak
  - ST_Slope

* #### Checking Outliers of All Columns

* #### Handling Outliers

### Data Preprocessing

* #### Checking Number of Unique Values of Categorical Features

* #### Data Transformation

* #### Normalization / MinMaxScaler()

* #### Merge the transformed columns

* #### Train-Test Split

* #### Balancing (SMOTE Oversampling)

* #### Principal Component Analysis (PCA)

### Modeling

* #### Using Random Forest Classifier for Modeling

* #### Checking Feature Importance

* #### Model Evaluation

* #### Feature Selection

* #### Hyperparameters Tuning using GridSearchCV

### Conclusions

* #### Test Accuracy Score: 0.8768115942028986
* #### Test Precision: 0.9032258064516129
* #### Test Recall: 0.8805031446540881
* #### Test ROC AUC Score: 0.87614900822448
