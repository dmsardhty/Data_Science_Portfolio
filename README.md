# Contents

## [1. McDonald's Nutritional Facts Analysis and Menu Recommendation](https://github.com/dmsardhty/McDonalds-Nutrition-Facts)

For this project, I obtained the dataset from [Kaggle](https://www.kaggle.com/mcdonalds/nutrition-facts) and begin to analyzed the defined business problem. The overall work that i can bring from this project is listed below : 

* Determined the calories average of 9 McDonald's menu categories.
* Discovered the spesific calories average of Beverages, Coffee & Tea, and Smoothies & Shake excluded from McDonald's foods menu.
* Compared the nutritional value qualities of McDonald's grilled chicken vs crispy chicken menu.
* Identified McDonald's menu nutrition which use whole eggs and white eggs.
* Analyzed the minimum order amount of selected McDonald's menu based on its nutritional value by approaching the one day nutritional requirements.
* Using basic recommender system to suggests the suitable menu based on certain nutrition values.

I majorly used an Exploratory Data Analysis (EDA) with some visualizations like Bar Chart, Pie Chart, and Correlation Map to obtain the results of defined problem whilst on the last point, I tried to make some improvement from this dataset by using clustering machine learning method which is recommender system in order to ease the output i desire.
      
_Tools: Numpy, Pandas, Matplotlib, Seaborn_                                                                                                                     
_Method: Exploratory Data Analysis, Recommender System_


## [2. Nepal Earthquake : Damage Prediction of Destructed Building & Prevention Suggests](https://github.com/dmsardhty/Damage-Prediction)

This is my second project that i got when joining data science bootcamp. The dataset was retrived from [drivendata.org](https://www.drivendata.org/competitions/57/nepal-earthquake/). This project was ran in groups consists of four people to gain a new insights based on defined business problem. Overall work that we conduct in this project are:

* Recommended the best material and specific building characteristic to resist further earthquake damage based on EDA results.
* Splitted the data into 80% train and 20% test during model building in order to apply, train, and validate the selected algorithm before deployed to test dataset.
* Classified over 86.000 data of damaged building into 3 damage categories (Low, Average, and High) using Random Forest Classifier.
* Tuned the model using RandomizedSearchCV to reach the optimum solution caused by model overfitting.

The reason we choose Random Forest Classifier is the imbalance of the data and many outliers during EDA phase. Furthermore, We were able make a model to predict the damage with 88,5% F1 Score after execute the hyperparameter tuning to reduce model overfitting and enhance the low F1 score using RandomizedSearchCV.

_Tools: Scikit-learn, Numpy, Pandas, Matplotlib, Seaborn_                                                                                                                     
_Method: Exploratory Data Analysis, Random Forest Classifier, RandomizedSearchCV_


## [3. Potential Customer Prediction for Increasing Product Sales](https://github.com/dmsardhty/Increasing-Product-Sales)

At November 2020, there was an online workshop held by Algoritma Data Science School that explain the CRISP-DM approach for solving business problem. The workshop was mainly guide the participants on using R language to do this approach. Hence, I try to recreate this workshop project by using Python with a similar approach but I put an improvisation on the data preparation and modelling phase. The dataset were uploaded by the workshop presenter on the google drive so the participant could use it for training. In this recreate project, the results that i could generate are: 

* Increased sales profit by 3200 (approximation = $200000) based on cost-benefit analysis according to applied machine learning models.
* Performed a medium-complex data pre-processing consists of data cleansing, typo fixing, index changing, label encoding, and one-hot encoding.
* Compared Decision Tree, Support Vector Machine, Random Forest Classifier, and Light GBM model performance.
* Obtained the feature importance according to the used model.
* Plotted some valuation distribution with or without outliers, and frequency heatmaps.

Although the model used were only achieve the 70% accuracy which dont reach the business goals (>75% accuracy), the overall work still successfully increase the profit. There are several early diagnose that makes the model dont reach >75% for instance; Dirty or improper input data and Data gathering is not in real time yet. 

_Tools: Scikit-learn, Numpy, Pandas, Matplotlib.pyplot, Seaborn_                                                                                                                     
_Method: Decision Trees, Random Forest Classifier, Light GBM, EDA, Label Encoding, One-Hot Encoding
