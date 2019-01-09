# ML-Flight-Delay-Prediction
Prediction of flight delays in the United States using the dataset provided by the [Bureau of Transportation Statistics](https://www.transtats.bts.gov/glossary.asp). Different ML techniques such as NN, Regression, Ridge/Lasso Regression were implemented before choosing the best model.

Contains two code files, one for NN, and one Regression

1. In the beginning, we peform data pre-processing and do feature, selection, encoding in pandas.

2. Then, we convert the data to numpy array. (x_train) and (y_train). We can input them in our 
algorithms (NN) and Regression).

3. Note that for NN, we use Pytorch library. So we convert numpy array in tenors when we are doing NN.

4. Then, different regression types and techniques were tried in the end. 
