<h1 style="text-align:center">CUSTOMER CHURN PREDICTION</h1>
<br>
<h2>Description</h2>

<p>Customer churn prediction task consists of creating model capable of predicting customer churn for subscription in a Bank.The dataset used in this task is available in <a style='text-decoration:none' href='https://www.kaggle.com/datasets/shantanudhakadd/bank-customer-churn-prediction'> kaggle</a>.It's the dataset of a U.S. bank customer for getting the information that , this particular customer will leave bank or not.
Data contains 14 features two of them are categorical features and the rest are numerical. Also it's divided into two groups customers who will leave the bank and who will not.</p>

<h2 style="color:gray,text-align:center">Proposed approach</h2>
The proposed approach for predecting customer churn consists of three modules.
<ul><li>
Data Preprocessing:In general data is incomplete and contains some noise. The aim of this module is to increase the quality of data to be useful in a such model. First of all we treate missing and outliers values, in our case data doesn't contain any null value.
All the features have different scale therefore we use a technique called feature scaling to normalize the range of variables and to have the same importance. For the categorecal data we use feature encoding that consists of converting categorecal feature to numerical feature, there are several ways to perform feature encoding depending on the type of categorical feature(nominal, Ordinal).</li><br>
 <li> 
Choosing the best model:in this task we have a classification problem and there are a lot of methods to train model. After spliting data into ttrain and test data we can use technique colled cross validation to evaluate and to choose the best model. It consists of spliting training data into K subset called folds and then training model on k-1 folds and evaluate it by the rest.</li><br>
<li>Fine-tuning model: consists of choosing the best combination of hyperparameters that gives more accurate results.</li>
