# ds_module_20_Credit_Risk_Classification
In this Challenge, I'lluse various techniques to train and evaluate a model based on loan risk. I’ll use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

First the data was split into Traning and Testing Sets. A corrilation and heat map were then used to select features, and a scaler applied to those features. AFter splinting into test and training datasets, a logistic regression model was made with the training data. After saving the results, the model then ran the test.

  * The liner regression resulted in 90 false positives and 12 false negatives
  * The test might be a little over fit
  * The F1 score for the high-risk loans makes the model look pretty good
  * The Recall is a little low (I would recomend a model that kept it above .90)
  * On the whole the model seems fine enough, but I would compair it to several other models
