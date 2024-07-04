
# PHISHING DETCETION USING MACHINE LEARNING

This project aims to classify SMS messages as either "spam" or "ham" (non-spam) using machine learning techniques. It involves data preprocessing, feature extraction using text vectorization, and training a classification model.



## LIBRARIES USED
Libraries Used

numpy: For numerical operations.

pandas: For data manipulation and handling.

seaborn: For data visualization.

string: For string operations.

nltk.corpus: For stopwords removal.

matplotlib.pyplot: For plotting.

sklearn: For machine learning algorithms and metrics.
## DATASET
The dataset used in this project  consists of SMS messages labeled as "ham" or "spam". It contains 5,572 messages originally with multiple columns, but only 'v1' (target label) and 'v2' (message text) are used for analysis.
##Data Cleaning
Removed unnecessary columns containing mostly NaN values.
Dropped duplicate messages to avoid bias in the training set.
## Exploratory Data Analysis (EDA)
Visualized the distribution of spam vs. non-spam messages using a pie chart.
Checked for class imbalance and handled it using appropriate techniques.

## Data Preprocessing
Renamed columns for clarity (v1 to TARGET, v2 to MESSAGE).
Converted the categorical target variable (TARGET) into numerical format using Label Encoding.

## Feature Engineering
Utilized CountVectorizer from Scikit-learn to convert text messages into numerical vectors for model training.
Split the dataset into training and testing sets using a 80-20 split.
## Model Selection and Training
Employed Logistic Regression as the classification model due to its efficiency and interpretability.
Trained the model on the training set and achieved an accuracy of 99.76% on the training data and 99.81% on the test data.
## RESULT
Evaluated model performance using accuracy metrics on both training and test sets.

Demonstrated high accuracy in predicting spam and non-spam messages, showcasing the effectiveness of the trained model.

This project successfully implemented a text classification solution for SMS spam detection using machine learning. The model achieved high accuracy rates on both training and test datasets, indicating its potential for practical applications in real-world scenarios.
## FUTURE DEVELOPMENTS
1. Experiment with other machine learning algorithms (e.g., Support Vector Machines, Naive Bayes) for comparison.
2. Implement more advanced text preprocessing techniques (e.g., stemming, lemmatization) to enhance model performance.
## MADE BY
1.AMISHI BHAMRA

2.KARANBIR PAHAWA