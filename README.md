# DS-Project
> Author: Nan Liu

This repository contains some data science projects and is only for self-learning purpose.

[Predict the loan repayment capacity using tensorflow]()
> python, jupyter notebook

>tensorflow, keras, pandas, numpy, matplotlib, seaborn, sklearn

- Perform data preprocessing, remove or fill any missing data,  remove unnecessary or repetitive features and convert categorical string features to dummy variables

- Split the original data into train and test dataset
- Use the MinMaxScaler to normalize the feature data X_train and X_test
- Define the Neural Network with 4 layers, 3 dropout layers to predict binary classification
- Split the original data into train and test dataset
- Plot out the validation loss versus the training loss and conclude our model prevented overfitting
- Predict on the test set, print out the confusion matrix, and conclude our model has accuracy about 89%.

[Linear Regression to predict Boston Housing](https://github.com/nan-hub/DS-Project/blob/master/Linear%20Regression%20to%20predict%20Boston%20Housing.ipynb)

> python, jupyter notebook

>pandas, numpy, matplotlib, seaborn, sklearn

- Import Boston Housing data from sklearn datasets
- Visualize the data and find the parameters which are highly associated with the housing price
- Split the original data into train and test dataset
- Train the model and provide interpretaion of coefficient
- Predict on the test set and report MAE, MSE and RMSE

[Classify spam and ham messages using NLP](https://github.com/nan-hub/DS-Project/tree/master/NLP%20classification)
> python, jupyter notebook

> pandas, nltk, saborn, plotly, sklearn

- Import the csv files with pandas
- Perform data preprocessing, remove the punctuation and the stopwords
- Use CountVectorizer to convert a collection of text documents to a matrix of token counts
- Transform integer counts to weighted TF-IDF scores
- Choose Naive Bayes classifier to train on TF-IDF vectors
- Write a pipleline of normalization workflow
- Train the data, report the confusion matrix and classification report

[Visualize stock prices](https://github.com/nan-hub/DS-Project/blob/master/Finance%20Project.ipynb)
> python, jupyter notebook

> pandas, saborn, plotly, cufflinks

- Use `pandas_datareader` to fetched the online bank stock data from yahoo finance for Bank of America, CitiGroup, Goldman Sachs, JPMorgan Chase, Morgan Stanley
and Wells Fargo
- Visualize the stock returns for each bank and analyze the outstand points
- Create interactive plot with plotly and cufflinks

[Movie Recommendation with Recommender Systems](https://github.com/nan-hub/DS-Project/tree/master/Movie%20Recommendation%20with%20Recommender%20Systems)
> python, jupyter notebook

>pandas, numpy, matplotlib, seaborn

- Create histogram to analysis the number of rateing
- Filter out the movies with less than 100 ratings
- Calculate the correlation between the chosen viewed movie and the other movies
- Recommend the most similar movies (highest correlation)

*Note: This is a simplified model!*


