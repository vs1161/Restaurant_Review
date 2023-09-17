# Restaurant_Review - NLP Project

Dataset - Downloaded from Kaggle containing ( 10000 * 8 ) dimension 
Data preprocessing has been done using:
                - nltk library 
                - word lemmatization technique
                - removing regular expressions
                - removing StopWords 
                    
The reviews are text therefore the text has been converted into vectors of words so that it is interpretable by computer 
               - using the TF-IDF technique 

The transformed data has been split into (80:20) train and test datasets leveraging sklearn 
The dataset has been trained in several models for accuracy observation:
                     1. Logistic Regression
                     2. Random Forest Classifier
                     3. KNN 
                     4. Gaussian NavieBayes classifier 
                     5. Multinomial NavieBayes classifier 
                     6. Support Vector Machine classifier 

The accuracy of all models has been compared:
![restaurant_review](https://github.com/vs1161/Restaurant_Review/assets/106301220/51d6ab34-d28f-4ebb-afbf-367e3e0a87cc)
