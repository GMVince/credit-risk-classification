# Credit-Risk-Classification Challenge
![](/images/istockphoto.jpg)
# Instructions
The instructions for this Challenge are divided into the following subsections:

Split the Data into Training and Testing Sets

Create a Logistic Regression Model with the Original Data

Predict a Logistic Regression Model with Resampled Training Data

Write a Credit Risk Analysis Report

## Split the Data into Training and Testing Sets

![Train_Test_Split](/images/train_test_split.png)

## Create a Logistic Regression Model with the Original Data

![Logistic_Regression](/images/LR_Model.png)

## Predict a Logistic Regression Model with Resampled Training Data

![Predictions](/images/predict.png)

##  Credit Risk Analysis Report

The cm_oversampled_df report has a 99% accuracy when identifying a low risk loan and 100% accuracy in not identifying a high risk loan as a low risk loan. Identifying the High risk loans has a lower accuracy of 91% with an 85% precision score. This will easily identify low risk loans but the high risk loans seem to be a more difficult to identify and may take more investigation to accurately identify.
# After Resampling with RandomOverSampler module:
There is a much better balance of the data now. Both high and low risk loans are identified with 98-96% accuracy and the precision of the data is 96-98%.
This appears to be a very good evaluation of high and low risk loans.
![balance](images/_754842bc-89bd-4477-bf29-6077910e287b.jpg)

## Resources:
pictures
https://www.istockphoto.com/illustrations/credit-risk
https://www.bing.com/images/create/accurate-credit-risk-predictions/6463943a99fb4580bde76b5e6fb88d84?FORM=GENCRE

ChatGPT - checking syntax
https://chat.openai.com/

scikit-learn - definitions for scikit functions
https://scikit-learn.org/stable/modules/generated/sklearn.metrics.precision_recall_fscore_support.html


stackoverflow for error corrections
https://stackoverflow.com/

