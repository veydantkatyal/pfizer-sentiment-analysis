# Pfizer Vaccine Sentiment Analysis

## Project Overview
This project aims to analyze public sentiment towards the Pfizer COVID-19 vaccine using Natural Language Processing (NLP). The analysis leverages social media data (e.g., Twitter), applies sentiment classification techniques, and visualizes trends in vaccine-related discussions.

## Dataset
- **Source:** [Pfizer Vaccine Tweets-Kaggle](https://www.kaggle.com/datasets/gpreda/pfizer-vaccine-tweets)
- **Format:** CSV files containing columns such as `tweet_id`, `text`, `date`, `sentiment`, `user_location`.
- **Classes:**
  - Positive (Supportive sentiments about Pfizer vaccine)
  - Negative (Skeptical or adverse reactions)
  - Neutral (Informational or indifferent tweets)

## 🛠️ Technologies Used
- **Programming Language:** Python
- **Libraries:**
  - `pandas` 
  - `nltk` & `TextBlob` 
  - `matplotlib` & `seaborn`

## 🔧 Installation
To set up the environment and dependencies, follow these steps:

```bash
# Clone the repository
git clone https://github.com/veydant-katyal/pfizer-sentiment-analysis.git
cd pfizer-sentiment-analysis

# Create a virtual environment
python -m venv venv
source venv/bin/activate   # On Windows use `venv\Scripts\activate`

# run colab notebook
directly load .ipynb file and run on Google colab

```

## 🚀 Results & Findings
- The analysis reveals key trends in public sentiment towards the Pfizer vaccine.
- A majority of tweets are **positive**, reflecting public trust.
- Some negative tweets highlight **concerns regarding side effects**.
- Neutral tweets mainly consist of **news articles and official announcements**.

## 📌 Future Enhancements
- Use **Topic Modeling** (LDA) to identify key concerns and discussions.
- Deploy a trained model as a **real-time sentiment analysis API**.

## 📝 License
This project is licensed under the [MIT License](https://github.com/veydantkatyal/pfizer-sentiment-analysis/blob/main/LICENSE)
