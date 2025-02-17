# 📊 Sentiment Analysis on Social Media Data  

## 📌 Project Description  
This project performs **Sentiment Analysis on Social Media Data**, specifically Twitter data, to classify tweets as **Positive, Negative, or Neutral**.  
It utilizes **VADER Sentiment Analysis**, text cleaning, and visualization techniques to analyze sentiment trends.  

## 🚀 Features  
- 📌 **Cleans raw text** (removes URLs, mentions, hashtags, and extra spaces).  
- 🔍 **Performs sentiment analysis** using VADER (Positive, Negative, Neutral).  
- 📊 **Visualizes sentiment distribution** using bar charts.  
- ☁️ **Generates word clouds** for frequently used words in positive tweets.  
- 📝 **Allows user input** to analyze any custom tweet's sentiment.  

## 📂 Dataset Information  
- The dataset used is `Twitter_Data.csv`, containing real Twitter reviews.  
- **Column Used:** `clean_text` – contains preprocessed tweets.  
- If using your own dataset, make sure it has a column with text data.  


### 1️⃣ **Install Dependencies**
pip install pandas matplotlib wordcloud vaderSentiment

### 2️⃣ **Run the Script**
python sentiment_analysis.py

### 🎯 **Usage**
Running Sentiment Analysis on Dataset
The script loads Twitter_Data.csv, cleans the text, and classifies sentiment.
A bar chart and a word cloud are displayed.
Predict Sentiment for a Custom Tweet
Enter any tweet when prompted:


![image](https://github.com/user-attachments/assets/b1ed6124-da78-450d-ac4d-0348a50c12a9)
![image](https://github.com/user-attachments/assets/0d17f72b-ac16-46d8-aa01-185e418fc2d2)

### Novality
Emoji & Slang-Based Sentiment Analysis 🎭
Many sentiment models fail with emojis or internet slang.
Example:
"This update is 🔥🔥🔥" → Positive
"This phone is 💀" → Negative



## 🛠 Installation & Setup  
### 3️⃣ **Clone the Repository**  
```bash
git clone https://github.com/your-username/sentiment-analysis.git
cd sentiment-analysis


