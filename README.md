# Credit_Risk_Analysis
Credit_Risk_Analysis
## OVERVIEW OF ANALYSIS
The purpose of this analysis was to use several different machine learning models to predict credit risk. We used oversampling, undersampling, "SMOTEENN" and random forests to create an ensemble of machine learning techinques. The following is a summary of the results
#### Resources
Jupyter notebook, class resource files, scikitlearn
## Results

Confusion matrix
![image](https://user-images.githubusercontent.com/100965117/180887099-00fbda1c-5a01-4e0d-9710-12589308abeb.png)

#### smote
![image](https://user-images.githubusercontent.com/100965117/180887240-18dd7af6-dde8-4fbb-b9cc-62c6346f627d.png)


![image](https://user-images.githubusercontent.com/100965117/180887269-1210c21a-f011-41a8-bde5-0e678e96c5bc.png)

#### cluster
![image](https://user-images.githubusercontent.com/100965117/180887303-e33e67af-c4dd-40fc-a0ee-fe0aa8fd180b.png)

#### random forest classification
![image](https://user-images.githubusercontent.com/100965117/180887803-8384e883-456f-4dd6-9568-99a83c66cf81.png)



## summary 
All the models used to perform the credit risk analysis show weak precision in determining if a credit risk is high.
The Ensemble models brought a lot more improvment specially on the sensitivity of the high risk credits.
The EasyEnsembleClassifier model shows a recall of 92% so it detects almost all high risk credit. On another hand, with a low precision, a lot of low risk credits are still falsely detected as high risk which would penalize the bank's credit strategy and infer on its revenue by missing those business opportunities.
For those reasons I would not recommend the bank to use any of these models to predict credit risk.
