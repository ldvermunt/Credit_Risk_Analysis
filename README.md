# Credit_Risk_Analysis
## Overview
A comprehensive data set consisting of historical credit card holder account information formed the base of this project.  Using my knowledge of machine learning, I was able to apply six different classifiers the data in order to modify sampling or adjust algorithms on each and determine which was best suited to predict instances of account default.  After transforming the string data into numerical type I ran a "Random Oversampler", "SMOTE", "Cluster Centroids", "SMOTEENN", "Random Forest" and "Easy Ensemble" classifiers.  The results were as follows.
## Results
# Random Oversampler
![image](https://user-images.githubusercontent.com/111530580/209217306-4fc46379-db2f-4db0-b5ae-b2bd9f8833f6.png)
# SMOTE (Oversampling)
![image](https://user-images.githubusercontent.com/111530580/209218852-221df5d6-2841-4666-82b3-5b29ba4a0f2d.png)
# Cluster Centroids (Undersampling)
![image](https://user-images.githubusercontent.com/111530580/209219062-bbaf7f93-3007-4332-bc2a-b0799baf5cc7.png)
# SMOTEENN (Over/Undersampling)
![image](https://user-images.githubusercontent.com/111530580/209219200-d028a4e0-c496-44e5-8996-bf6f39d67c92.png)
# Balanced Random Forest (Algorithm)
![image](https://user-images.githubusercontent.com/111530580/209230369-50000a99-3320-49b1-bfc9-8b8788117635.png)
# Easy Ensemble (Algorithm)
![image](https://user-images.githubusercontent.com/111530580/209219470-1263eafc-5c66-4e62-8eb8-d98c47893f1f.png)
## Summary
In this example, the credit card company is interested in filtering out as many possible future defaulters as they can while not denying those who will honor thier bills. Ideally they would be able able to find a high precision and recall.  This is closest in the Easy Ensemble algorithm.   However the Balanced random forest ended up with a precision on the high risk data points of 0.88, I believe it is an error requiring further analysis.


  
