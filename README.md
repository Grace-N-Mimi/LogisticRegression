Throughout this project, there are some important things i have learnt worth documenting about the sklearn library one used in Machine learning
Sklearn is a python library for machine learning that features models in both supervised and unsupervised learning
In this specific case sklearn was used in the following instances
1. Preprocessing.
The sklearn.preprocessing package provides common utility functions and classes to standardize, normalize and even encode features
The main use was the standardScaler function used to scale data into assuming the Z-standard- distribution. This is to enhance the effectiveness of the model
2. Splitting data into testing and training data
This is done using sklearn.modelselection package
3. constructing the regression model
This is done using the package called sklearn.linear_model where one imports their lnear model of choice
There are many linear models that can be called such as Logisticregression, lasso, regression etc
4. Evaluating the model
This was done using the sklearn.metrics which has many metrics for many models and one picks the most suitable for the model
In this case, the most suitable metrics functions were classification report and confusion matrix. Metrics seem to have other metrics to evaluate other models too 
