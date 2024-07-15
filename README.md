## Intel Products Sentiment Analysis from Online Reviews

This project aims to analyze sentiment from online reviews of Intel i7 and i9 processors. The following steps outline the process undertaken to achieve this goal.

### 1. Data Exploration
**Description**: 
The initial phase involves sourcing datasets from Kaggle that contain user reviews for Intel i7 and i9 processors. This step includes understanding the dataset's structure, identifying key features, and summarizing the data to gain preliminary insights.

### 2. Problem Statement
**Description**: 
The primary challenge addressed in this project is the multilingual nature of the data. Reviews are written in various languages, necessitating additional preprocessing steps to ensure uniformity and accuracy in sentiment analysis.

### 3. Data Cleaning
**Description**: 
Data cleaning involves preparing the dataset for analysis by handling missing values, correcting inconsistencies, and ensuring that the data is in a usable format. This step is crucial for maintaining the integrity and quality of the data.

### 4. Language Translation
**Description**: 
Since the reviews are in multiple languages, this step involves translating all reviews into a single language (e.g., English) using automated translation using pretrained model 'Helsinki-NLP/opus-mt-mul-en. This ensures consistency and allows for accurate sentiment analysis.

### 5. Punctuation Removal
**Description**: 
This preprocessing step involves removing punctuation from the text data. Punctuation can introduce noise into the dataset and affect the performance of text analysis algorithms.

### 6. Duplicate Records Removal
**Description**: 
Identifying and removing duplicate reviews is essential to prevent bias and ensure that the analysis reflects unique user sentiments accurately.

### 7. Dropping Unwanted Columns
**Description**: 
The dataset may contain columns that are irrelevant to the analysis. This step involves identifying and removing such columns to streamline the dataset and focus on the most relevant information.

### 8. Sentiment Analysis
**Description**: 
Sentiment analysis involves using Natural Language Processing (NLP) techniques to determine the sentiment expressed in each review. This can be classified as positive, negative, or neutral sentiment.

### 9. Data Classification
**Description**: 
Classifying the sentiment data into predefined categories (positive, negative, neutral) enables a structured analysis of user sentiments towards Intel i7 and i9 processors.

### 10. Data Analysis
**Description**: 
This step involves analyzing the classified data to identify trends, patterns, and insights into user sentiments. Visualization tools and statistical methods are employed to interpret the results.

### 11. Sentiment Prediction
**Description**: 
Building models to predict the sentiment of new, unseen reviews based on the patterns learned from the training data. This step leverages machine learning algorithms to enhance the accuracy of sentiment classification.

### 12. Data Conversion on X-Axis, Y-Axis
**Description**: 
Transforming the data into a suitable format for visualization, where the X-axis represents different variables (e.g., time, product version) and the Y-axis represents sentiment scores or counts.

### 13. Train-Test Split
**Description**: 
Splitting the dataset into training and testing sets to evaluate the performance of sentiment analysis models. The training set is used to train the models, while the testing set is used to assess their accuracy and generalizability.

### 14. Predictions Using Multiple Models
**Description**: 
Employing various machine learning models (e.g., Logistic Regression, SVM, Random Forest) to predict sentiments and comparing their performance to select the best model for the task.

### 15. Conclusion
**Description**: 
Summarizing the findings of the project, discussing the effectiveness of the models used, and providing insights into user sentiments towards Intel i7 and i9 processors. This section also highlights potential areas for future work and improvement.

