# Credit_Risk_Analysis

## Overview
The purpose of this analysis is to predict credit risk. We are using credit card data from LendingClub, a peer-to-peer lending services company.

We will employ different machine learning models to evaluate and make recommendations on which will be best to evaluate credit risk.

## Results
Here are the results of the six machine learning models:


- Naive Random Oversampling

![image](https://user-images.githubusercontent.com/111028230/213936945-a2599596-c13a-4842-a4b5-2af3dc3c45ee.png)
![image](https://user-images.githubusercontent.com/111028230/213936959-20850ec4-e1bb-4101-a330-54f1598f76c0.png)


- SMOTE Oversampling

![image](https://user-images.githubusercontent.com/111028230/213936977-c28ecb0a-0397-40c9-9126-243717f593b1.png)
![image](https://user-images.githubusercontent.com/111028230/213936986-2f78e907-713e-4955-9324-5dd4fd56e36a.png)


- Undersampling

![image](https://user-images.githubusercontent.com/111028230/213937017-ab0b4ef8-061a-40e8-a3ed-cbbe5751d653.png)
![image](https://user-images.githubusercontent.com/111028230/213937026-13464442-e226-472f-920d-8a005fae1a26.png)


- Combination (Over and Under) Sampling

![image](https://user-images.githubusercontent.com/111028230/213937038-b888b898-000d-427e-ac7b-6091c0d90a2f.png)
![image](https://user-images.githubusercontent.com/111028230/213937052-efd4806d-cd16-4627-b83f-c3b1bf8b2c8c.png)


- Balanced Random Forest Classifier

![image](https://user-images.githubusercontent.com/111028230/213937696-aafd2799-66e0-41a2-96a2-4d161928976f.png)
![image](https://user-images.githubusercontent.com/111028230/213937185-795da040-84fd-4269-911c-b4f320b85295.png)


- Easy Ensemble AdaBoost Classifier

![image](https://user-images.githubusercontent.com/111028230/213937205-bfbf2542-7fce-442f-91b8-6be3a47528dd.png)
![image](https://user-images.githubusercontent.com/111028230/213937211-3f24ccb6-2d52-4155-a885-3e3c06f196df.png)


## Summary
After analyzing all six machine learning models, the Easy Ensemble AdaBoost Classifier would be the one recommended.

The Easy Ensemble AdaBoost Classifier had the highest in the balance accuracy score (92.5%) and the recall score (94%). However, althought the Easy Ensemble AdaBoost Classifier was the model that scored the highest in determining credit risk, it is not perfect. There is still a percentage that would be listed as false positives. It is recommended there is a system in place for the human intervention for that percentage.
