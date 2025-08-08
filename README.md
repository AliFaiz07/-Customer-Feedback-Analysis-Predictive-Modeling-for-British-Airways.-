# ✈️ Customer Feedback Analysis & Predictive Modeling for British Airways

A data analytics and machine learning project for **British Airways** aimed at extracting actionable insights from customer feedback and predicting future customer bookings.

This project combines **web scraping, natural language processing (NLP), and predictive modeling** to support strategic decision-making, improve customer satisfaction, and boost customer acquisition.

---

## 📌 Project Objectives
1. **Customer Feedback Analysis** – Scrape and analyze customer reviews from Skytrax to uncover sentiments, common topics, and service improvement areas.
2. **Predictive Modeling for Customer Acquisition** – Build a machine learning model to forecast customer bookings based on historical booking data.

---

## 🛠 Technologies & Tools
- **Programming Language:** Python  
- **Libraries:** BeautifulSoup, Pandas, NumPy, scikit-learn, Matplotlib, Seaborn, NLTK, WordCloud  
- **Machine Learning Model:** Random Forest Classifier  
- **Techniques:** Sentiment Analysis, Topic Modeling, Feature Engineering, Model Evaluation  
- **Data Visualization:** Matplotlib, Seaborn  
- **Data Sources:** Skytrax reviews (web scraping) & provided customer booking dataset

---

## 📂 Project Workflow
1. **Web Scraping**
   - Collected British Airways customer reviews from Skytrax using BeautifulSoup.
   - Extracted ratings, comments, and other relevant attributes.

2. **Data Cleaning & Preprocessing**
   - Removed special characters and stopwords.
   - Applied lemmatization for text normalization.
   - Converted qualitative ratings to numeric values.

3. **Exploratory Data Analysis (EDA)**
   - **Sentiment Analysis:** Classified reviews as Positive, Negative, or Neutral.
   - **Topic Modeling:** Identified recurring themes in customer feedback.
   - **Word Clouds:** Visualized frequently mentioned words.

4. **Predictive Modeling**
   - Prepared customer booking dataset with feature engineering.
   - Trained a **Random Forest** model to predict booking likelihood.
   - Evaluated using Accuracy, Precision, Recall, and F1-score.
   - Analyzed **feature importance** to identify key booking drivers.

5. **Insights & Presentation**
   - Created impactful visualizations and a concise summary for business stakeholders.
   - Delivered findings in a single-slide format for board-level discussions.

---

## 📊 Key Insights
- Common negative sentiments involved delays, baggage handling, and seat comfort.
- Positive reviews focused on crew friendliness and in-flight service quality.
- Predictive model achieved strong performance in identifying likely bookings.
- Top booking influencers included ticket price, flight duration, and loyalty membership.

---

## 🚀 How to Run
1. Clone the repository:
```bash
git clone https://github.com/<your-username>/british-airways-feedback-prediction.git
cd british-airways-feedback-prediction
