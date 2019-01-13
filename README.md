# ML-Projects
Credit Card Default Prediction 


Stock Return Prediction seeks to uncover the strongest drivers of stocks return for the medium to long term. Stocks information
from the NYSE and NASDAQ were used for the project.
To achieve the goal of the project, fundamental data were collected from https://simfin.com/ whereas return data were scraped
from yahoo finance. 
Financial metrics from the income statement, cash flow statement and balance sheet were collected. A total of 63 variables were used as
attributes and these include amongst others: Book-Value/Market Capitalization, Price/Sales, Price/Book, EBIT/EV(Enterprise Value),
EV/EBITDA, EV/FCF(Free Cash Flow), etc.
For the purpose of this project, the core problem (what are the strongest drivers of stock return?) lies within the supervised 
machine learning space. Given the challenges with accurate prediction of fure stock prices, this project seeks to separate 
all stocks into two categories, good and bad stocks. This then becomes a classification problem. The next question is what makes a stock 
a good stock? In answering this question, a benchmark index was chosen which is the S&P500. Stocks that outperform the index within 
the period (one year) are classified as **good stocks**, whereas all others are classified as **bad stocks**. 
Machine Learni algorithms ranging from simple classifiers such as **Logistic Regression, Decision Tree, K-Nearest Neighbor, Naive Bayes** 
to more sophisticated algorithms such as **Support Vector Machine, ensemble methods e.g. Bagging, Ada Boost, Random Forest, 
Gradient Boosting, XGBoost, Stacking Classifier** and to more state-of-the-art models such as **Artificial Neural Network (ANN).**
The dataset is an imbalanced one, therefore, in the second part of the project, classical methodologies and metrics 
beyond just accuracy were used. These include metrics such as Precision, Recall, F1 Score, AUC, ROC curve, Lift curve, 
use of cross validation/hyperparameter tuning, ensemble methods, data resampling techniques, etc.
The last part of the model seeks to filter a subset or very important features that significantly explain changes in 
stocks return (the dependent variable).
