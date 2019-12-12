# predict-loan-repayment
machine learning algorithms o predict the repayment ability/ default behavior of the client. 

how to run this code:
step 1: unzip the project folder and create a folder and name it as 'data'
step 2: download data from here (data source)https://www.kaggle.com/c/home-credit-default-risk/data. 
        put all data inside the data folder.
step 3: use ipython notebook to run the python code.


what included here:
there are two programs included applicationData.ipynb and application_burearu.ipynb. 
applicationData.ipynb : 
	descriptive statistics,
	data preparation steps,
		missing data handing,
		outlier analysis, 
		data normalization, 
		data encoding,
		dimension reduction,
		feature importance and so on.
		
After above tasks, used machine learning algorithms knn, logistic regression, svm for binary classifications to predict the application_train data set svm (linear kernel) perform well than other above mentioned algorithms. Model performance was measured by confusion matrix. 

application_burearu.ipynb: 
this python code used for tables joins, aggregations is to figure out more effective features that helpful to  buildup a robust model and for improve the accuracy.
