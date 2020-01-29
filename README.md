This is a 1 week data challenge on predicting conversion probability for each offer. Specifically, if a user clicks on a lender's loan offer, the models will accurately predict the probability that the user will ultimately take a loan from that lender. 

The dataset is a sample of the offers that users have clicked on in the past including information on both the lead (e.g., the user's self-reported credit rating, income, etc) and the offers that they clicked on (e.g., the loan amount offered, APR, etc).

Here, I designed a two stage model using latent representation from autoencoder and SVM to achive a 0.81 AUC score with 0.18 false positive rate and 0.21 false negative rate.


![Model](https://github.com/cl3080/Predicting-User-Conversion/blob/master/Screen%20Shot%202020-01-29%20at%209.35.54%20AM.png)


The code can be found here:

[**Jupyter notebook**](http://htmlpreview.github.io/?https://github.com/cl3080/Predicting-User-Conversion/blob/master/Predict_user_conversion.html)
