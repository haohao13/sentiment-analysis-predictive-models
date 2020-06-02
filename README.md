# Sentiment Analysis Predictive Classification Models

## Dataset
1. Data Type: Amazon product review data (Health and Personal Care)  
2. Dataset size: ~346,000  
3. Dataset location:  
http://snap.stanford.edu/data/amazon/productGraph/categoryFiles/reviews_Health_and_Personal_Care_5.json.gz  

## Process
1. Apply various text representation techniques (Bag of Words, TF-IDF, n-Grams) for text vectorization.  
2. Develop Sentiment Analysis predictive models (binary classification) in Python. Apply Logistic Regression, Decision Tree, Random Forest classification algorithms.  
3. Apply GridSearchCV to find the best hyperparameters for the previous models.
4. Assess model performance (confusion matrix, precision, recall, ROC AUC).
### Conclusion: Among all 9 models, the logistic regression model using TF-IDF text representation technique has the best performance.
