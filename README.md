# chatgpt_reviews_analysis
Sentiment and subjectivity analysis of ChatGPT reviews using TextBlob in Colab.
📊 ChatGPT Reviews Analysis
🧾 Overview
This project analyses user reviews of ChatGPT using Natural Language Processing (NLP) techniques in a Jupyter Notebook (Google Colab). The primary goal is to gain insights into user sentiments and understand how subjective or objective the reviews are.

📌 Objectives
Load and clean ChatGPT review data.

Use TextBlob to compute:

Sentiment Polarity (positive vs. negative tone)

Sentiment Subjectivity (subjective opinion vs. factual statement)

Visualise the overall sentiment trends.

Interpret the distribution and behaviour of reviews.

🔍 What Was Done
Imported the dataset and performed basic data cleaning.

Defined custom functions using TextBlob to extract:

Polarity: ranging from -1 (very negative) to 1 (very positive)

Subjectivity: ranging from 0 (objective) to 1 (subjective)

Applied these metrics to each review.

Plotted histograms and distribution graphs to:

Visualise the spread of polarity and subjectivity scores.

Identify patterns in review tone.

Discussed insights based on the output plots.

📈 Key Findings
Most reviews cluster around neutral to slightly positive polarity, suggesting users generally have a favourable opinion.

Many reviews showed high subjectivity, meaning users shared personal opinions more than facts.

Some reviews had negative polarity, offering constructive criticism or expressing dissatisfaction.

🛠️ Technologies Used
Python (in Google Colab)

Pandas

TextBlob (for sentiment analysis)

Matplotlib / Seaborn (for data visualisation)

✅ Conclusion
This analysis provides a quick yet powerful overview of how users perceive ChatGPT based on written reviews. Using simple NLP tools like TextBlob, we can effectively gauge user satisfaction and identify areas of improvement from textual feedback.

📁 Files Included
CHATGPT_Reviews_Analysis.ipynb – Main analysis notebook

chatgpt_reviews.xlsx – Source dataset

README.md – This file
