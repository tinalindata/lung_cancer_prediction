# Lung Cancer Prediction
###### Tina Lin &bull; 12/2018

&nbsp;
## Data Source 
The dataset that I use is a National Lung Screening Trail (NLST) Dataset that has 138 columns and 1,659 rows. 1,659 rows stand for 1,659 patients. There is a “class” column that stands for with lung cancer or without lung cancer. The other columns are features of the patients, such as “age”, “height”, “education”, etc. The dataset is provided by a professor at the State University of Arkansas and I am a remote volunteer for his lung cancer research project.

&nbsp;
## Motivation
Lung cancer causes more deaths than any other cancer. The odds for men is 1 in 13 while that for women is 1 in 16. Therefore, 
I want to create a model which can find the best features for lung cancer prediction. It can be used to aid the doctors in the decision making process and improve the disease identification process. 

&nbsp;
## Methods
### Feature Selection
1. **RandomForest embedded pagckages in H2O**
2. **Weight of Evidence and Information Value (https://github.com/h2oai/h2o-meetups/blob/master/2017_11_29_Feature_Engineering/Feature%20Engineering.pdf)** (better performance)

### Models
1. **DecisionTree Classifier**
2. **GradientBoosting Classifier**
3. **LogisticRegression Classifier**
4. **XGBoost Classifier**


