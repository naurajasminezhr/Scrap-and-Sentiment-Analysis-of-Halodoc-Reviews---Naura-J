# Scrap-and-Sentiment-Analysis-of-Halodoc-Reviews-by-Naura-J
This repository contains a comprehensive guide to scraping and analyzing reviews from Halodoc, a popular healthcare platform in Indonesia. The project involves web scraping to collect review data, preprocessing the data, and performing sentiment analysis to understand the overall sentiment of the reviews.

# Overview
This repository provides a step-by-step guide on how to scrape and analyze reviews from Halodoc using Python. The project aims to extract relevant data from the website, preprocess the text data, and perform sentiment analysis to determine the overall sentiment of the reviews.

# Prerequisites
Python 3.x: The project requires Python 3.x to run.
Pandas: For data manipulation and analysis.
Seaborn: For creating visualizations.
Scikit-learn: For preprocessing and sentiment analysis.
BeautifulSoup: For web scraping.
Requests: For making HTTP requests.

# Installation
To set up the environment, follow these steps:
Install Required Libraries:

To set up the environment, follow these steps:
## 1. Install Required Libraries:
```
pip install pandas seaborn scikit-learn beautifulsoup4 requests
```

## 2. Clone the Repository:
```
git clone https://github.com/your-username/scrap_and_sentiment_analysis_halodoc_reviews.git
```

## 3. Navigate to the Repository:
```
cd scrap_and_sentiment_analysis_halodoc_reviews
```

#### Function

The repository includes the following functions:

1. **Web Scraping**:
   - The `scrap_and_sentiment_analysis_halodoc_reviews.ipynb` Jupyter Notebook contains the code for web scraping reviews from Halodoc using BeautifulSoup and Requests.

2. **Data Preprocessing**:
   - The notebook includes steps to clean and preprocess the scraped data, such as removing special characters and converting text to lowercase.

3. **Sentiment Analysis**:
   - The notebook uses Scikit-learn's `TfidfVectorizer` and `MultinomialNB` to perform sentiment analysis on the preprocessed data.

4. **Visualization**:
   - The notebook includes code to create scatter plots using Seaborn to visualize the sentiment polarity and subjective scores.

#### Library

The project utilizes the following libraries:

- **Pandas**: For data manipulation and analysis.
- **Seaborn**: For creating visualizations.
- **Scikit-learn**: For preprocessing and sentiment analysis.
- **BeautifulSoup**: For web scraping.
- **Requests**: For making HTTP requests.

#### Get Started

To get started with the project, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/scrap_and_sentiment_analysis_halodoc_reviews.git
   ```

2. **Navigate to the Repository**:
   ```bash
   cd scrap_and_sentiment_analysis_halodoc_reviews
   ```

3. **Open the Jupyter Notebook**:
   ```bash
   jupyter notebook scrap_and_sentiment_analysis_halodoc_reviews.ipynb
   ```

4. **Run the Notebook**:
   - The notebook will guide you through each step of the process, from web scraping to sentiment analysis.

#### Train

The training process involves the following steps:

1. **Web Scraping**:
   - Run the code in the `scrap_and_sentiment_analysis_halodoc_reviews.ipynb` notebook to scrape reviews from Halodoc.

2. **Data Preprocessing**:
   - Clean and preprocess the scraped data as described in the notebook.

3. **Sentiment Analysis**:
   - Use Scikit-learn's `TfidfVectorizer` and `MultinomialNB` to perform sentiment analysis on the preprocessed data.

4. **Visualization**:
   - Create scatter plots using Seaborn to visualize the sentiment polarity and subjective scores.

#### Evaluation Score

The evaluation score can be calculated by comparing the predicted sentiments with the actual sentiments. Here’s an example of how you can evaluate the model:

```python
from sklearn.metrics import accuracy_score, classification_report

# Predicted sentiments
predicted_sentiments = model.predict(X_test)

# Actual sentiments (assuming X_test contains the test data)
actual_sentiments = y_test

# Calculate accuracy score
accuracy = accuracy_score(actual_sentiments, predicted_sentiments)
print("Accuracy:", accuracy)

# Print classification report
print("Classification Report:")
print(classification_report(actual_sentiments, predicted_sentiments))
```



