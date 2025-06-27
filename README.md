# 🌐 Social Media Sentiment Analysis Using NLP

## 🧠 About the Project
This project focuses on analyzing public sentiments from social media platforms like Twitter using Natural Language Processing (NLP). The aim is to classify text into **Positive**, **Neutral**, or **Negative** sentiments using tools like **TextBlob** and **VADER**, and visualize the overall trend and key insights to support brand perception strategies.

---

## 🎯 Objectives
- Clean and preprocess user-generated content.
- Apply sentiment analysis using TextBlob and VADER.
- Classify and visualize sentiment categories.
- Detect sentiment spikes over time.
- Recommend strategies to improve brand perception.

---

## 📁 Dataset
- **Source**: Kaggle  
- [Dataset Link](https://www.kaggle.com/datasets/kashishparmar02/social-media-sentiments-analysis-dataset)
- **Format**: CSV  
- **Key Column**: `text` (user content)

---

## 🛠️ Tools & Technologies Used
- **Python** (Google Colab)
- `pandas`, `numpy`
- `nltk`, `re`
- `TextBlob`, `vaderSentiment`
- `matplotlib`, `seaborn`, `wordcloud`

---

## 🔄 Workflow

### 1. Data Collection
- Loaded CSV dataset into Google Colab
- Verified dataset structure and null values

### 2. Preprocessing
- Lowercased text
- Removed URLs, mentions, hashtags, punctuation, numbers
- Tokenized, removed stopwords, and lemmatized text

### 3. Sentiment Analysis
- Applied TextBlob and VADER for polarity scoring
- Created new columns with sentiment labels
- Used VADER for final classification due to social media focus

### 4. Visualizations
- Word cloud of frequent words
- Bar chart for sentiment counts
- Sentiment trend plot over tweet index

### 5. Sentiment Spike Detection
- Detected sudden spikes in positive/negative sentiment
- Visualized with line plots and markers

---

## 📈 Key Results
- Majority of tweets were **positive**
- **Negative spikes** related to delivery delays or support issues
- Word cloud revealed most-used terms like *love*, *delay*, *quick*, *best*

---

## 💡 Recommendations to Improve Brand Perception
- Monitor and respond to negative feedback quickly
- Promote positive user content
- Encourage user-generated stories (UGC)
- Run campaigns to increase positive engagement
- Address operational pain points like delivery delays
- Maintain transparent communication

---

## 🚧 Challenges Faced
- No date column in dataset, used index for trends
- Difficulty classifying sarcasm or short tweets
- Manual upload required in Colab

---

## 🔮 Future Scope
- Live tweet analysis using Twitter API
- Topic modeling using LDA
- Real-time dashboards with Streamlit
- Multilingual sentiment classification

---



> *This project helped me gain hands-on experience with real-world NLP tasks and understand how brands can benefit from data-driven sentiment analysis.*


