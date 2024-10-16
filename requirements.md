A key area of knowledge in data analytics is the ability to extract meaning from text. This assignment provides the foundational skills in this area by detecting whether a text conveys a positive or negative message.

Analyze the sentiment (e.g., negative, neutral, positive) conveyed in a large body (corpus) of texts using the NLTK package in Python. Complete the steps below. Then, write a comprehensive technical report as a Python Jupyter notebook to include all code, code comments, all outputs, plots, and analysis. Make sure the project documentation contains a) Problem statement, b) Algorithm of the solution, c) Analysis of the findings, and d) References.

Preliminary: Explore the data sets suitable for sentiment analysis by accessing the "Sentiment Analysis Dataset," located in the topic Resources. Select a data set to use in this project.

Import the necessary Python modules: numpy, pandas, matplotlib, seaborn, BeautifulSoup, and nltk.

Import the data set you chose to use in this project.

Preprocess and Visualize the Data:

Perform a descriptive statistical analysis of the data and decide how to handle missing values.
Store your data in a dataframe.
Count the number of positive, negative, and neutral text items, as tagged by a score in one of the columns.
Display your findings in a plot.
Build the Model:

Remove punctuation!
Remove stop words (i.e., words that do not add a sentiment).
Assign each word in every text element, with a sentiment score (use TfidVectorizer).
Use a binary classification algorithm (e.g., logistic regression), which you can import from sklearn.
Divide the data into a training set and testing set, with a ratio of 80:20.
Fit the data set using the model.
Compute the (accuracy) score of the model.
Make Predictions:

Enter several questions and assess the sentiment they convey.
Evaluate the Model:

Create a confusion matrix to assess the overall performance.
Present the performance metrics and visualize the findings.
Summarize the project, explaining to what extent it is suitable to perform sentiment analysis.
