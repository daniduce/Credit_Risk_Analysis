# Credit_Risk_Analysis

## Overview of the analysis: 

With the machine learning models we are using this to help solve the problem of credit risk and how it can be an unbalanced classification problem. We used a credit file from Lending Club that uses credit card data. The company wants to use a machine learning model in order to help better assess which candidates are loan worthy. We have used several different algorithms in order to reduce bias and find out which one is the best to help predict high or low risk loans.


## Results:

* Naive Random Oversampling

<img width="570" alt="Screen Shot 2021-03-06 at 3 07 51 PM" src=https://user-images.githubusercontent.com/71396367/110219682-c0cc4380-7e8e-11eb-907f-17c35199ced3.png>

For the Naïve Random OverSampling Machine model the accuracy scores sits at 64%. 

<img width="314" alt="Screen Shot 2021-03-06 at 4 05 55 PM" src=https://user-images.githubusercontent.com/71396367/110220772-d8f39100-7e95-11eb-80c8-b59468af2327.png>

High risk sit at a precision rate of 10% and recall of 66%. Low Risk sit at a precision rate of 100% and recall of 62%. This brings the average precision to 99% and recall to 62%.


* Smote Oversampling

<img width="480" alt="Screen Shot 2021-03-06 at 3 15 56 PM" src=https://user-images.githubusercontent.com/71396367/110219709-e1949900-7e8e-11eb-9c28-bf03c71d47e0.png>

For the Smote OverSampling Machine model the accuracy scores sits at 65%. 

<img width="310" alt="Screen Shot 2021-03-06 at 4 06 18 PM" src=https://user-images.githubusercontent.com/71396367/110220779-e872da00-7e95-11eb-8c08-a8c0c42f3280.png>

High risk sit at a precision rate of 10% and recall of 61%. Low Risk sit at a precision rate of 100% and recall of 69%. This brings the average precision to 99% and recall to 69%.


* Undersampling

<img width="565" alt="Screen Shot 2021-03-06 at 3 16 42 PM" src=https://user-images.githubusercontent.com/71396367/110219746-fffa9480-7e8e-11eb-8340-69621337d77d.png>

For the Undersampling Machine model the accuracy scores sits at 65%. 

<img width="322" alt="Screen Shot 2021-03-06 at 4 06 43 PM" src=https://user-images.githubusercontent.com/71396367/110220786-f88ab980-7e95-11eb-9bea-b0e5bde79db1.png>

High risk sit at a precision rate of 10% and recall of 68%. Low Risk sit at a precision rate of 100% and recall of 41%. This brings the average precision to 99% and recall to 41%.


* Combination

<img width="569" alt="Screen Shot 2021-03-06 at 3 18 30 PM" src=https://user-images.githubusercontent.com/71396367/110219782-3b955e80-7e8f-11eb-8ca3-5fb8992404d9.png>

For the Combination Machine model the accuracy scores sits at 55%. 

<img width="324" alt="Screen Shot 2021-03-06 at 4 07 12 PM" src=https://user-images.githubusercontent.com/71396367/110220794-080a0280-7e96-11eb-8bec-9052e03b0a2a.png>

High risk sit at a precision rate of 10% and recall of 72%. Low Risk sit at a precision rate of 100% and recall of 57%. This brings the average precision to 99% and recall to 57%.


* Balanced Random Forest Classifier

<img width="576" alt="Screen Shot 2021-03-06 at 3 19 20 PM" src=https://user-images.githubusercontent.com/71396367/110219808-5d8ee100-7e8f-11eb-8666-cbbf2162dcff.png>

For the Balanced Random Forest Classifier Machine model the accuracy scores sits at 79%. 

<img width="318" alt="Screen Shot 2021-03-06 at 4 07 53 PM" src=https://user-images.githubusercontent.com/71396367/110220805-207a1d00-7e96-11eb-9249-5228c1bda9cf.png>

High risk sit at a precision rate of 3% and recall of 70%. Low Risk sit at a precision rate of 100% and recall of 87%. This brings the average precision to 99% and recall to 87%.


* Easy Ensemble Adaboost Classifier

<img width="564" alt="Screen Shot 2021-03-06 at 3 20 12 PM" src=https://user-images.githubusercontent.com/71396367/110219828-78615580-7e8f-11eb-9e34-0d2f5ad340f4.png>

For the Easy Ensemble Classifier Machine model the accuracy scores sits at 93%. 

<img width="326" alt="Screen Shot 2021-03-06 at 4 08 16 PM" src=https://user-images.githubusercontent.com/71396367/110220814-2ec83900-7e96-11eb-8b92-0da52e3a9a19.png>

High risk sit at a precision rate of 9% and recall of 92%. Low Risk sit at a precision rate of 100% and recall of 94%. This brings the average precision to 99% and recall to 94%.


## Summary: Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.

