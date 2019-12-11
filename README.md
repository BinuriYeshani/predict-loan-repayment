# predict-loan-repayment
machine learning algorithms o predict the repayment ability/ default behavior of the client,

use ipython note book editor to run this

data source: https://www.kaggle.com/c/home-credit-default-risk/data

applicationData.ipynb : included the descriptive statistics,
			data preparation steps- missing data handing,
			outliers data identify steps, 
			data normalization, 
			data encoding,
			dimension reduction.
I used stratified sampling for data set separation into test and training purpose because of imbalance of the data. So accuracy, precision, recall values are not a valid measure for this situation. I used knn , logistic regression, svm for binary classifications to predict the application_train data set svm (linear kernel) perform well according to the confusion matrix results than other algorithms

application_burearu.ipynb: 
I joined application training and bureau data set into together, purpose is to figure out more attributes to training model and increase accuracy.
