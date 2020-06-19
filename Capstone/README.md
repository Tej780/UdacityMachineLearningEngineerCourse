# Machine Learning Engineer Capstone Project

An Amazon SageMaker project that defines and LSTM model to predict the relevance and role of a job advertisement based on it's description.

The [dataset](https://www.kaggle.com/sl6149/data-scientist-job-market-in-the-us) comes from kaggle user Shanshan Lu who scraped 7000 US job listings from Indeed.com.

The project makes use of the following Python modules:
- Pandas and Numpy for data structure and processing

- Matplotlib, PIL and wordcloud for exploration and visualisation

- Scikit-learn and statsmodel for preprocessing and validation metrics

- NLTK for language processing

- Sagemaker and Pytorch for model creation and deployment

JobRelevanceClassifier.ipynb contains a Binary Classification model to predict job relevance.

RoleMultiClassifier.ipynb contains a MultiClassifier the categorises roles as Data Science, Machine Learning Engineer, Data Analyst, Software Engineer or Data Engineer. It is assumed roles have already been selected by relevance.

Both notebooks should run sequentially end-to-end and independantly. The initial cells can be run without Sagemaker, and a re useful to testing purposes.

