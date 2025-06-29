### Project Title
Capstone 20.1 EDA of Fetal Health Dataset

**Author**
Jundi Wang

#### Executive summary
This report presents an exploratory data analysis (EDA) and initial machine learning modeling conducted as part of the capstone project. The objective of this phase was to understand the important feature for fetal health by gaining a comprehensive understanding of the dataset through visual and statistical exploration of the development of baseline predictive models. 

The Executive steps are list as below:
1. We began by importing and inspecting the dataset, followed by systematic data cleaning. 
2. We visualized the correlcation Metrix of the dataset to understand the dataset.
3. We randomly splitted dataset for training and testing purposes.
4. We build different type of base model, including LinearRegression, KNN, DecisionTree, SVR, VotingRegressor and GradientBoostingClassifier, to cross validate the base models performanse. Also, we used these base models to verify the important features for fetal health. 
5. We printed MSE performance of each base model and visualized the important features 

#### Rationale
Fetal health is very important to parenting before fetal is produced. It allows us to detect abnormal health condition as early as possible and help us to involing the treatment, including taking appropriate medicine or nutritions, to help fetal survive.  

#### Research Question
What medical data is helping for idenfiying fetal health ?

#### Data Sources
fetal_health data set from https://www.kaggle.com/

#### Methodology
1. We began by importing and inspecting the dataset, followed by systematic data cleaning. 
2. We visualized the correlcation Metrix of the dataset to understand the dataset.
3. We randomly splitted dataset for training and testing purposes.
4. We build different type of base model, including LinearRegression, KNN, DecisionTree, SVR, VotingRegressor and GradientBoostingClassifier, to cross validate the base models performanse. Also, we used these base models to verify the important features for fetal health. 
5. We printed MSE performance of each base model and visualized the important features 

#### Results
After comparing the coefficiency or important feaure of each base model. The most robust predictors across model types are: prolongued_decelerations, abnormal_short_term_variability, and percentage_of_time_with_abnormal_long_term_variability. On the other hand, features like fetal_movement and severe_decelerations offer minimal predictive value, particularly in tree-based and permutation-based models.

#### Next steps
I will recommend pregnant to pay attention of above important feature, including prolongued_decelerations, abnormal_short_term_variability, and percentage_of_time_with_abnormal_long_term_variability, during routine check. 

#### Outline of project
- [Capstone_20_1_Inital_Report_and_EDA](https://github.com/wjd20170117/Capstone_20_1_Inital_Report_and_EDA/blob/main/Capstone_20_1.ipynb)

##### Contact and Further Information
No prefer to provide personal information. 
