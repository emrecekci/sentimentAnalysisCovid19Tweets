# Sentiment Analysis of Social Media Posts About COVID-19 Vaccines Using Machine Learning Techniques

## ‎Description
With the increasing use of social media, people share their feelings and thoughts and interact with each other on social media in many different areas ranging from daily issues to the services they purchase. Especially X (formerly Twitter) is the social media platform where this interaction is the most intense. Tweets shared on this platform constitute a source of dataset for researchers. New vaccine studies and developments that started with the COVID-19 pandemic have caused different feelings and thoughts among people. By using this source code, it is aimed to find the machine learning algorithm that gives the best result by analyzing people's emotions on COVID-19 vaccine tweets. Decision Tree, Random Forest, Multinomial Naive Bayes, Multinomial Logistic Regression, and Support Vector Machine (SVM) classification algorithms were used. SVM with linear kernel trick had the highest success rate. As a result, we recommend the use of Support Vector Machine learning model in predicting sentiment analysis of COVID-19 vaccine posts. Thus, this knowledge can be used by the government officials and the health specialists for decision and policy making.

## ‎Dataset Information
A third party dataset which is available at https://www.kaggle.com/datasets/gpreda/all-covid19-vaccines-tweets, was used.

## Code Information

The code was implemented in Python and developed using Jupyter Notebook environment.

## ‎Usage Instructions
First, dataset should be downloaded and the downloaded file (vaccination_all_tweets.csv) should be placed under same folder with the tez_kod.ipynb file. Then the source code should be executed.

## ‎Requirements – Any dependencies
‎Pandas, Numpy, SciKit-Learn, NLTK, Mathplotlib packages were used for machine learning, whereas VADER (Hutto and Gilbert, 2014) and TextBlob (Loria et al., 2024) software libraries were used to do sentiment analysis and calculating polarities of the X posts.