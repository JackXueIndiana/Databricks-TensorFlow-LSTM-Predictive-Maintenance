# Databricks-TensorFlow-LSTM-Predictive-Maintenance
In this repo we will show you how to set up Databricks clsuter and run Python 3 with keras and tensorflow for LSTM model against the same dataset for the predictive maintenance. 

A cluster is Standard v 4 Databricks clsuter is created with mix of 2 and max of 8 DS3_V2 workders. Libraries keras and tensorflow were loaded using PyPi.

The dataset for the predictive maintenance is from

http://azuremlsamples.azureml.net/templatedata/PM_train.txt

http://azuremlsamples.azureml.net/templatedata/PM_test.txt

http://azuremlsamples.azureml.net/templatedata/PM_truth.txt


Noticing that the AUC is much better than our previous example:

precision =  0.9744915546363323 

 recall =  0.9119354838709678
 
auc =  0.9530150645753371
