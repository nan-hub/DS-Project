# DS-Project
> Author: Nan Liu

This repository contains some data science projects and is only for self-learning purpose.

[Predict the loan repayment capacity using tensorflow](https://github.com/nan-hub/DS-Project/blob/master/Keras_predict_loan_payback.ipynb)
> python, jupyter notebook

>tensorflow, keras, pandas, numpy, matplotlib, seaborn, sklearn

- Performed data preprocessing, removed or filled any missing data,  removed unnecessary or repetitive features and converted categorical string features to dummy variables

- Splited the original data into train and test dataset
- Used the MinMaxScaler to normalize the feature data X_train and X_test
- Defined the Neural Network with 4 layers, 3 dropout layers to predict binary classification
- Splitted the original data into train and test dataset
- Plotted out the validation loss versus the training loss and concluded that our model prevented overfitting
- Predicted on the test set, printed out the confusion matrix, and concluded our model has accuracy about 89%.

[Linear Regression to predict Boston Housing](https://github.com/nan-hub/DS-Project/blob/master/Linear%20Regression%20to%20predict%20Boston%20Housing.ipynb)

> python, jupyter notebook

>pandas, numpy, matplotlib, seaborn, sklearn

- Imported Boston Housing data from sklearn datasets
- Visualized the data and found the parameters which were highly associated with the housing price
- Splitted the original data into train and test dataset
- Trained the model and provided interpretaion of coefficients
- Predicted on the test set and reported MAE, MSE and RMSE

[Classify spam and ham messages using NLP](https://github.com/nan-hub/DS-Project/tree/master/NLP%20classification)
> python, jupyter notebook

> pandas, nltk, saborn, plotly, sklearn

- Imported the csv files with pandas
- Performed data preprocessing, removed the punctuation and the stopwords
- Used CountVectorizer to convert a collection of text documents to a matrix of token counts
- Transformed integer counts to weighted TF-IDF scores
- Chose Naive Bayes classifier to train on TF-IDF vectors
- Writed a pipleline of normalization workflow
- Trained the data, reported the confusion matrix and classification report

[Visualize stock prices](https://github.com/nan-hub/DS-Project/blob/master/Finance%20Project.ipynb)
> python, jupyter notebook

> pandas, saborn, plotly, cufflinks

- Used `pandas_datareader` to fetch the online bank stock data from yahoo finance for Bank of America, CitiGroup, Goldman Sachs, JPMorgan Chase, Morgan Stanley
and Wells Fargo
- Visualized the stock returns for each bank and analyzed the outstand points
- Created interactive plot with plotly and cufflinks

[Movie Recommendation with Recommender Systems](https://github.com/nan-hub/DS-Project/tree/master/Movie%20Recommendation%20with%20Recommender%20Systems)
> python, jupyter notebook

>pandas, numpy, matplotlib, seaborn

- Created histogram to analysis the number of rateing
- Filtered out the movies with less than 100 ratings
- Calculated the correlation between the chosen viewed movie and the other movies
- Recommended the most similar movies (highest correlation)

*Note: This is a simplified model!*


