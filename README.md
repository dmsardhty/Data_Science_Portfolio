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

_Tools: scikit-learn, Numpy, Pandas, Matplotlib, Seaborn_                                                                                                                     
_Method: Exploratory Data Analysis, Random Forest Classifier, RandomizedSearchCV_
