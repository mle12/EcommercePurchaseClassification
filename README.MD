# Ecommerce Purchase Classification

To view this file please go to https://nbviewer.org. To render please enter link https://github.com/mle12/EcommercePurchaseClassification/blob/main/week2__final.ipynb

To build a model to predict whether an item will be purchased using E commerce data. I used large datasets involving various features including session time, time of day and number of sessions. I first needed to determine which features were the most important to include. I used python and the pandas library to read and analyse the data. I then used matplotlib to visualise the correlation between the various features. I dropped the features with high correlation and then fit various classifiers on the remains ones. The models used included a Support Vector Machine, Gradient Boosted tree ad Randomn Forest. I then determined which classifier performed better using metrics such as Accuracy, Precision, Recall and F1 score.
I found that the SVM performed best providing 99% accuracy on the test data.


## Screenshots

![Ecommerce Purchase Classification](./EPC.png)
