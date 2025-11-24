🧠 Fake Job Posting Detection Using NLP

Using Machine Learning to Detect Fraudulent Job Listings

📌 Overview

This project aims to detect fake or fraudulent job postings using Natural Language Processing (NLP) and Machine Learning techniques. With the rise of job scams on online platforms, this model helps automatically identify suspicious listings and improve user safety.

📂 Dataset

The dataset used in this project:
fake_job_postings.csv

Contains job descriptions along with a label indicating whether the post is real or fraudulent.

Link to notebook (uploaded by user):
https://colab.research.google.com/drive/1AZKVsK-xwoIZ9fyfDq-Oq4a518jamoNi


🚀 Project Workflow
1️⃣ Data Preprocessing

Handled missing values

Removed irrelevant columns

Applied text preprocessing (tokenization, stopwords removal, lemmatization)

2️⃣ Exploratory Data Analysis (EDA)

Fraud vs Real job distribution

Word frequency analysis

WordCloud visualizations

3️⃣ Feature Engineering

TF-IDF Vectorization

Bag-of-Words representation

NLP metadata features

4️⃣ Model Training

Used machine learning models such as:

Model	Status
Logistic Regression	✔️ Tested
Random Forest	✔️ Tested
SVM	✔️ Tested
Naïve Bayes	✔️ Tested
XGBoost / BERT	🚧 (Future Work)

5️⃣ Evaluation Metrics

Accuracy

Precision, Recall, F1-score

Confusion Matrix

ROC–AUC Curve

🧾 Technologies Used
Category	Tools
Language	Python
NLP	NLTK, spaCy, TF-IDF
ML	Scikit-learn
Visualization	Matplotlib, Seaborn, WordCloud
Deployment (Future)	Flask / Streamlit

📈 Results

Achieved high precision on fake job detection

Found that job descriptions and companies with unusual wording were strongly correlated with fraud

Potential for real-world deployment in HR & job portals

📌 Future Improvements

Deploy as web app using Streamlit/Flask

Integrate API for real-time job filtering

Use deep learning models (BERT, LSTM)

Improve dataset balance using SMOTE
