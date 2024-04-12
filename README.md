# SP500-Predictor

- Utlized the yahoo finance library to import S&P500 numbers since its creation
- Removed certain elements such as 'Dividends' and 'Stock Splits' that did not influence predictions
- Created a column using the pandas library for a 'Tomorrow' value
- Used the RandomForestClassifier method from the Ensemble class from the Scikit-learn library to create a model
    - Used the method to train and test different parts of the dataset
- Created methods to predict and backtest the predictors determined
- Decided to use ratios instead of whole values to determine an improved precision score
- Changed predict to further improve what ratio is determined as a useful ratio
    - Included usage of the RandomForestClassifier method from Scikit-learn library and the pandas library to change the table from num py
