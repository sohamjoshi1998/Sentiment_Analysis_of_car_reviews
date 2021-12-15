# Sentiment_Analysis_of_car_reviews
Modeling a sentiment predictor of car reviews from social media
### Table of Contents
1. Overview
2. Motivation
3. Libraries Used
4. Methodology
5. Model Report
6. Author

### Overview:
To model a sentiment predictor (good or bad) - binary classification of user car reviews using Natural Language Processing(NLP)

### Motivation:
There are many social media platforms where people have the freedom to post their reviews about any car they recently purshased where they do not necessarily give a rating. In such cases, a machine learning model with the help of Natural Language Processing(NLP) can help predict the overall sentiment of the review which can help companies to analyze their product reviews.

### Libraries Used:
*NumPy, Pandas, Seaborn, Matplotlib,
nltk, re, wordcloud
Scikit_learn ML library*

### Methodology:
- The Suzuki car reviews dataset from Kaggle website has the following attributes - Date of the review, Name of the Author, Vehicle Title, Review Title, the actual detailed review and the corresponding rating given which will be our target variable.
- Cleaning the dataset by removing any missing values and standardizing all the data types.
- Dropping unnecessary columns and manipulating a few columns for analysis.
- Data processing and simplifying the target column - Rating as 0 or 1 for a binary classification problem (Rating>3 is a good review else a bad review)
- Visualizing the countplots of the binary classification reveals significant difference in the number of good and bad reviews.
- Adding another dataset (Ford car reviews from Kaggle website) to make the number of both the reviews comparable.
- Processing the new data as per the previous data processing.
- Data processing (Including leammatization) of the training set variables for NLP using NLTK and Scikit-learn libraries.
- Splitting the final dataset into traing and testing sets.
- Training a Random Forest model using the traing set and using hyperparameter tuning using GridSearchCV to optimize the model further.

### Model Report:
- The model achieved a 94.4% accuracy, 96.3% precision and a 92% recall score.

### Author:
Soham Joshi | [LinkedIn Profile](https://www.linkedin.com/in/sohamjoshi1998/)
