# Employee Sentiment Analysis Project

This project analyzes employee feedback using Natural Language Processing (NLP) to classify sentiment and identify employee flight risks. This is part of the **Final LLM Assessment**.

## 📁 Files in this Repo

- `llm_sentiment_project.ipynb` – Jupyter notebook with complete analysis
- `test(in).csv` – Raw dataset
- `processed_sentiment_data.csv` – Sentiment-labeled dataset
- `flight_risk_employees.csv` – List of employees at potential risk
- `monthly_sentiment_trend.png` – Monthly sentiment trend plot
- `regression_trend.png` – Linear regression of sentiment over time
- `sentiment_distribution.png` – Distribution of sentiment labels
- `wordcloud_positive.png` – Wordcloud for positive sentiments

## ⚙️ Setup Instructions

1. **Clone this repo** or download the ZIP
2. Make sure you have the following Python libraries installed:
```bash
pip install pandas numpy matplotlib seaborn wordcloud textblob scikit-learn
Run the notebook:

bash
Copy
Edit
jupyter notebook llm_sentiment_project.ipynb


📊 Methodology Overview

EDA: Exploratory Data Analysis on text column

Text Preprocessing: Cleaned and tokenized sentences

Sentiment Analysis: Used TextBlob to label each feedback as Positive, Neutral, or Negative

Visualization:

Sentiment distribution

Wordcloud of positive words

Monthly sentiment trends

Regression line to observe sentiment shift

Employee Ranking: Sorted based on average sentiment polarity

Flight Risk Detection: Employees with consistent negative feedback were flagged