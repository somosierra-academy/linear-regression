<h1>Linear Regression</h1>

Learn how math works behind the scenes of a machine learning model

Machine Learning use cases can be classified in two main groups:

* Regression: the output of the model in this case is numerical and the goal is to find the relationship between the input variables and the output variables. Regression models can be simple, such as linear regression, or more complex, such as polynomial regression. Examples of regression models can be the prediction of the value of a house, the temperature of a city or the price of a stock.

* Classification: you've already done it!. Classfication models are used to predict discrete values, such as whether an email is spam or not or whether a customer is likely to buy a product or not. In a classification model, the output variable is categorical and the goal is to find the relationship between the input variables and the output variable. We can divide classification models in three subgroups

  * Binary classification: the model predicts if the sample belongs to one of two mutually exclusive classes. For example, given a tomography, if there's cancer or not.
  * Multi-class classification: the model predicts if the sample belongs to one of more than 2 mutually exclusive classess.
  * Multi-label classification: the model predicts if the sample belongs to one or more classess at once.
  
Therefore, regression models are used to predict continuous values, while classification models are used to predict categorical values.

In this notebook we're going to build a Linear Regression model from scratch. We won't use any tool provided by Pytorch in order to set up the stages we used in the Outfit Classifier model
