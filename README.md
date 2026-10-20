# 🛡️ SpamGuard – Spam Mail Detection

SpamGuard is a Machine Learning-based web application that detects whether an email message is **Spam or Non-Spam** using TF-IDF and Logistic Regression. It provides a simple and user-friendly interface built with Gradio.

## 📌 Project Overview

Spam emails are unwanted messages that may contain advertisements, suspicious links, or fraudulent content. SpamGuard uses Machine Learning to analyze email text and predict whether a message is spam or non-spam.

The main objective of this project is to demonstrate how Machine Learning and Natural Language Processing (NLP) can be used for email text classification.

## ✨ Features

- 📧 Spam and Non-Spam email detection
- 🤖 Machine Learning-based text classification
- 🔤 TF-IDF text vectorization
- 📊 Logistic Regression classification model
- 🖥️ Interactive web interface using Gradio
- ⚡ Instant prediction results
- 🧹 Clear input option
- 📘 About and Contact sections

## 🛠️ Technologies Used

- Python
- Pandas
- Scikit-learn
- TF-IDF Vectorizer
- Logistic Regression
- Gradio
- Google Colab / Jupyter Notebook

## ⚙️ How It Works

1. **Data Collection:** Collect spam and non-spam email messages.
2. **Data Preprocessing:** Clean and prepare the email text.
3. **Label Encoding:** Assign `1` to Spam and `0` to Non-Spam.
4. **Feature Engineering:** Convert email text into numerical features using TF-IDF.
5. **Data Splitting:** Split the dataset into training and testing sets.
6. **Model Training:** Train a Logistic Regression model.
7. **Prediction:** Predict whether an email is Spam or Non-Spam.
8. **Model Evaluation:** Evaluate performance using Accuracy, Precision, Recall, and F1-score.
9. **Web Application:** Use Gradio to provide an interactive interface for users.

## 📂 Project Structure

```text
SpamGuard/
│
├── spam_mail_detection.ipynb
├── app.py
├── README.md
└── requirements.txt
```

*Note: Update the filenames according to the actual files in your repository.*

## 🚀 Installation and Setup

### 1. Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Navigate to the Project Folder

```bash
cd SpamGuard
```

### 3. Install Dependencies

```bash
pip install pandas scikit-learn gradio
```

### 4. Run the Application

```bash
python app.py
```

Make sure the trained `model` and `tfidf` vectorizer are available in your application before running it.

## 📊 Model Evaluation

The model can be evaluated using the following performance metrics:

- **Accuracy:** Measures the overall proportion of correct predictions.
- **Precision:** Measures how many emails predicted as spam are actually spam.
- **Recall:** Measures how many actual spam emails are correctly identified.
- **F1-Score:** Balances Precision and Recall.

Actual evaluation results depend on the dataset and model performance.

## 🎯 Project Objective

The objective of SpamGuard is to build a simple and practical Machine Learning application that helps identify unwanted emails and demonstrates the use of NLP techniques for text classification.

## 🔮 Future Improvements

- Display prediction confidence scores.
- Improve model performance with more training data.
- Compare Logistic Regression with Naive Bayes and other classifiers.
- Add email subject and sender analysis.
- Improve the user interface and responsive design.
- Deploy the application online for public access.

## ⚠️ Disclaimer

SpamGuard is an educational Machine Learning project. Predictions may not always be correct, and the application should not be used as the sole method for identifying fraudulent or malicious emails.

## 👨‍💻 Developer

**Piyal Baray**

📧 Email: [piyalbaray314@gmail.com](mailto:piyalbaray314@gmail.com)

---

⭐ If you find this project useful, consider giving the repository a star!

**Built with Python, Machine Learning, and Gradio.**
