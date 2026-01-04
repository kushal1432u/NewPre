# SMS Spam Detection System 📩🚫

A Machine Learning-powered web application that identifies whether an incoming SMS message is **Spam** or **Ham** (Legitimate). This project uses Natural Language Processing (NLP) to analyze text patterns and provide real-time predictions.

---

## 🚀 Features

* **Real-time Classification:** Instantly detect spam by typing or pasting a message into the UI.
* **Visual Feedback:** * 🔴 **Red Alert:** Clear indication for messages classified as **SPAM**.
    * 🟢 **Green Success:** Confirmation for legitimate **HAM** messages.
* **NLP Preprocessing:** Includes text cleaning, tokenization, and vectorization (TF-IDF/CountVectorizer) for high accuracy.
* **Web-Based Interface:** A clean, dark-themed dashboard built for easy user interaction.

---

## 🛠️ Technical Stack

* **Language:** Python 3.x
* **ML Libraries:** Scikit-learn, Pandas, NumPy
* **NLP Tools:** NLTK (Natural Language Toolkit)
* **Frontend:** Streamlit / Flask (Web UI)
* **Model:** Multinomial Naive Bayes / Random Forest (commonly used for this task)

---

## 💻 Installation & Setup

1. **Clone the repository**
   ```bash
   git clone [https://github.com/yourusername/sms-spam-detection.git](https://github.com/yourusername/sms-spam-detection.git)
   cd sms-spam-detection# NewPre
   Install dependencies

Bash

pip install -r requirements.txt
Run the Application

Bash

streamlit run app.py
🧪 How it Works
The system follows a standard NLP pipeline:

Input: User enters raw text (e.g., "pay $100 and get chance to win $200").

Preprocessing: The app removes stop words, punctuation, and converts text to lowercase.

Vectorization: Text is converted into numerical data that the computer understands.

Prediction: The trained model calculates the probability of the message being spam.

Output: The UI displays the result with color-coded labels.

📊 Dataset
This project is typically trained on the UCI SMS Spam Collection Dataset, containing over 5,000 labeled messages.
📝 License
This project is open-source under the MIT License.


---

## 📦 requirements.txt for SMS Spam Detection

This file includes the essential data science and web libraries required to run your spam filter.

```text
# Web Framework
streamlit

# Data Manipulation
pandas
numpy

# Machine Learning & NLP
scikit-learn
nltk
joblib

# Visualization (Optional but recommended for notebooks)
matplotlib
seaborn
