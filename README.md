# IndiaAI CyberGuard AI Hackathon

# Cybercrime Reporting NLP System

This project leverages advanced **Natural Language Processing (NLP)** techniques to enhance the process of filing cybercrime reports on the **National Cyber Crime Reporting Portal (NCRP)**. The system streamlines the reporting process by analyzing textual descriptions and supporting media files, identifying themes, and ensuring accurate and user-friendly submissions.

---

## 📌 Project Goals
- Simplify the process of filing cybercrime reports.
- Accurately classify cybercrime categories based on user descriptions.
- Provide actionable insights to law enforcement using data trends.

---

## 🚀 Features
- **Sentiment Analysis**: Detects tone and urgency of reports to prioritize cases.
- **Topic Modeling**: Identifies commonly reported themes like phishing, identity theft, and financial fraud.
- **Text Classification**: Categorizes criminal activities with high accuracy using a Random Forest Classifier.
- **Visual Insights**: Generates word clouds, confusion matrices, and sentiment trend graphs.

---

## 🛠️ Tech Stack
- **Programming Language**: Python
- **Libraries**: 
  - Data Handling: `Pandas`, `NumPy`
  - Text Processing: `spaCy`, `NLTK`, `re`
  - Machine Learning: `Scikit-learn`, `TF-IDF Vectorizer`
  - Visualization: `Matplotlib`, `Seaborn`, `WordCloud`

---

## 🔄 Workflow
1. **Data Loading and Cleaning**  
   - Load datasets, remove duplicates, and handle missing values.
2. **Exploratory Data Analysis (EDA)**  
   - Generate word clouds and analyze sentiment trends.
3. **Text Preprocessing**  
   - Perform tokenization, lemmatization, stopword removal, and feature extraction.
4. **Model Training and Evaluation**  
   - Train the Random Forest Classifier and evaluate using precision, recall, and F1-score.
5. **Visualization**  
   - Display feature importance, confusion matrices, and sentiment trends.

---

## 📊 Results and Insights
- The system captures key cybercrime themes and provides structured feedback for users.
- Sentiment analysis identifies peaks in negative sentiment to indicate spikes in criminal activity.
- The Random Forest Classifier achieves robust accuracy and handles high-dimensional text data effectively.
