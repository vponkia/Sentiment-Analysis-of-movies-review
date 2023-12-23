# Sentiment-Analysis-of-movies-review
### Dataset : https://snap.stanford.edu/data/web-Movies.html
### Overview :
Sentiment analysis project focused on utilizing LSTM models to analyze user sentiments within a vast dataset of first one million reviews. The primary objectives were to predict review helpfulness and sentiment(score) , with a keen interest in exploring the impact of combining 'Summary' and 'Text' features.

## Key Achievements

### Data Preprocessing:
Successfully loaded and cleaned the dataset, addressing missing values and ensuring the correct data types. Introduced a consolidated 'Concatenated_Text' feature by combining 'Summary' and 'Text' columns.

### Model Training and Evaluation:
1. Helpfulness Prediction with 'Text' and 'Summary' + 'Text':
Employed LSTM models for predicting review helpfulness using both individual 'Text' and concatenated 'Summary' + 'Text' features. Achieved a commendable test accuracy of approximately 75.15% for 'Text' and 73.40% for 'Summary' + 'Text.' Demonstrated adaptability in capturing nuanced patterns in review content, contributing to effective helpfulness predictions.

2. Sentiment Analysis (Score predection) with 'Text' and 'Summary' + 'Text':
Conducted sentiment analysis to categorize reviews into 'Negative,' 'Neutral,' and 'Positive' sentiments. The LSTM models showcased robust sentiment prediction, yielding a test accuracy of 84.51% for both 'Text' and 'Summary' + 'Text' combinations. Successfully captured nuanced sentiment variations within the reviews, highlighting the models' proficiency in understanding context and emotion.

### Consistent Training Parameters:
Maintained consistency in training parameters, including epochs, batch sizes, and Adam optimization, ensuring reliable model learning across all tasks. This consistency contributed to stable and reproducible results, enhancing the reliability of the sentiment analysis models.
