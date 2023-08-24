# Stock Sentiment Analysis Project

This project focuses on predicting whether stock price increased or decreased based on top 25 news headlines. It includes a dataset file `Data.csv` and a Jupyter Notebook file `notebook.ipynb` which contains the code.

## Dataset

- The data set in consideration is a combination of the world news and stock price shifts.
- Data ranges from 2008 to 2016 and the data from 2000 to 2008 was scrapped from Yahoo finance.
- There are 25 columns of top news headlines for each day in the data frame.
- Class 1- the stock price increased.
- Class 0- the stock price stayed the same or decreased.

## Notebook

The Jupyter Notebook file `notebook.ipynb` contains the code for the stock sentiment analysis project. Here is an overview of the steps performed in the notebook:

1. Importing required libraries.
2. Importing the `Data.csv` file.
3. Splitting training and testing dataset.
4. Cleaning the training text:
   - Removing Puncturations.
   - Lowering the text.
   - Removing stopwords.
   - Joining all 25 headlines in a single string.
5. Implementing Bag of Words with ngram_range = (1,2)
6. Defining Target Variable.
7. Training the Random Forest Classifier model.
8. Likewise training text, cleaning testing text.
9. Predicting for testing dataset.
10. Checking performance of model using accuracy score, confusion matrix and classification report.

Please refer to the `notebook.ipynb` file for detailed code implementation.