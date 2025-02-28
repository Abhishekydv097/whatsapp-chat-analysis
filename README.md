# WhatsApp Chat Analysis

## 📝 Project Overview
The **WhatsApp Chat Analysis** project is a Python-based tool designed to analyze and visualize WhatsApp chat data. It extracts meaningful insights from chat exports, like message frequency, active users, word usage, and sentiment trends, making conversations easier to interpret through interactive visualizations.

## 💡 Features
- **Data Cleaning & Extraction:** Uses Regex to extract structured data (date, time, user, message) from WhatsApp chat exports.
- **Message Analysis:** Identifies the most active users and busiest chat times.
- **Word Frequency:** Finds the most commonly used words, excluding stopwords.
- **Sentiment Analysis:** Classifies messages as positive, neutral, or negative.
- **Emoji Analysis:** Tracks the most frequently used emojis.
- **Data Visualization:** Uses Matplotlib and Seaborn for creating interactive charts.
- **Streamlit Web App:** Provides a user-friendly interface to upload and analyze chat data.

## 🛠️ Technologies Used
- **Python**
- **Pandas**
- **Matplotlib & Seaborn**
- **Regex (Regular Expressions)**
- **Streamlit**
- **NLTK (Natural Language Toolkit)**
- **WordCloud**

## 📂 Project Structure
WhatsApp-Chat-Analysis/ |-- app.py # Streamlit web app |-- chat_analysis.py # Core data processing and analysis |-- requirements.txt # Project dependencies |-- README.md # Project documentation

bash
Copy
Edit

## 🚀 How to Run
1. **Clone the Repository:**
```bash
git clone https://github.com/abhishekydv97/WhatsApp-Chat-Analysis.git
```
Navigate to the Project Directory:
```bash
cd WhatsApp-Chat-Analysis
```
Install Dependencies:
```bash
pip install -r requirements.txt
```

Install Dependencies:
```bash
streamlit run app.py

```
🧑‍💻 How It Works
## 🧑‍💻 How It Works
- **Upload the Chat File:** Export a WhatsApp chat and upload the `.txt` file.
- **Data Extraction:** The app parses the chat file, extracting date, time, user, and message.
- **Visual Insights:** Displays charts showing message frequency, active users, and common words.
- **Sentiment & Emoji Analysis:** Understand the tone and emotional context of the conversation.

## 📊 Sample Visualizations
- **Bar Chart:** Most active users.
- **Line Chart:** Messages over time.
- **Word Cloud:** Most used words.
- **Heatmap:** Busiest hours for messages.

## 📈 Future Enhancements
- **Support for Multimedia Messages.**
- **Advanced Sentiment Analysis Using ML Models.**
- **Group-Specific Analysis and Comparisons.**

## 📄 License
This project is open-source and available under the **MIT License**.
