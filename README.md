This repository features a logistic regression implementation along with data cleaning and Feature Engineering for Rain Prediction dataset at,  

https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package

achieving an accuracy of ~85% on test dataset.

Further it also explore approach of Decision Tree and Logistic Regression in sequence describing following approach.

    1. Select Appropriate Column (or set of columns, in this case "Location") to partition dataset
    2. For all the possible values of selected column group different classes based on cosine similarity of features of PCA Transformed Feature of Original Dataset. (In this case, 5 groups created having 10 categorical values each)
    3. For each of the segemented Dataset Train Different Logistic Regression Models. (5 Models in this case)

  This approach gives ~5% accuracy improvement in test dataset compared to regular logistic Regression approach.
