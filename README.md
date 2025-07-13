🛒 Flipkart Reviews Sentiment Analysis
This project demonstrates a complete end-to-end data science workflow:

Scraping real Flipkart product reviews 📝

Cleaning & preprocessing the text data 🧹

Exploratory Data Analysis (EDA) 📊

Building and evaluating sentiment prediction models 🤖

✨ Motivation
Customer reviews are a rich source of feedback for businesses.
Here, we extract Flipkart reviews to analyze customer sentiment (positive / neutral / negative) and build a predictive model to classify future reviews.

🚀 Workflow
📥 1. Data Collection
Used BeautifulSoup and requests to scrape reviews from Flipkart product pages.

Handled rate-limiting (status code 429) with randomized delays and retries.

🧹 2. Data Cleaning
Removed stopwords, punctuation using nltk.

Converted text to lowercase, tokenized words.

Combined title + review text into a single feature.

📊 3. EDA
Visualized word distributions for positive, neutral, and negative reviews using matplotlib and seaborn.

Checked class imbalance, frequent terms, and review length distributions.

🤖 4. Predictive Modeling
Transformed text into TF-IDF features.

Trained & compared multiple models:

Logistic Regression

SVM

Naive Bayes (Multinomial & Bernoulli)

Random Forest

Gradient Boosting

XGBoost

Evaluated with accuracy, precision, confusion matrices.

📂 Files
File	Description
scraper.py	Scrapes Flipkart reviews and saves as CSV
cleaning.py	Cleans & preprocesses text
eda.py	EDA visualizations
modeling.py	Builds & evaluates sentiment models
requirements.txt	Python dependencies
README.md	Project documentation

📋 Dataset
If you prefer to skip scraping, you can use the provided CSV (reviews.csv).

Column	Description
Title	Review title
Text	Review body
Rating	Star rating
Target	Sentiment class: Positive / Neutral / Negative

📦 Dependencies
beautifulsoup4

requests

pandas

numpy

nltk

scikit-learn

xgboost

matplotlib

seaborn

👨‍💻 Author
https://github.com/Ankush-Kumar-Jaiswal
www.linkedin.com/in/ankush-kumar-jaiswal-196937200



🌟 Contributing
Pull requests welcome!
If you have suggestions for improvements, feel free to open an issue.
