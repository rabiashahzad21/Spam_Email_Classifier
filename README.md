# 📧 Spam Email Classifier

A Machine Learning based web application that detects whether an email message is **Spam** or **Not Spam** using Natural Language Processing (NLP).

This project uses **TF-IDF Vectorization** to convert text into numerical features and **Multinomial Naive Bayes** for email classification. The trained model is deployed using a **Streamlit web application** for real-time predictions.

---

## 🚀 Features

- 📩 Detects spam and non-spam emails
- 🧹 Data cleaning and preprocessing
- 🔤 Text feature extraction using TF-IDF
- 🤖 Machine Learning classification
- 📊 Model accuracy evaluation
- 🌐 Interactive Streamlit interface
- 💾 Saved trained model and vectorizer
- ⚡ Real-time email prediction

---

## 🛠️ Technologies Used

- **Python**
- **Pandas**
- **Scikit-learn**
- **Streamlit**
- **Natural Language Processing (NLP)**
- **Machine Learning**

---

## 🧠 Machine Learning Workflow

1. Load email dataset
2. Clean and preprocess data
3. Split dataset into training and testing sets
4. Convert text data into numerical values using TF-IDF
5. Train Multinomial Naive Bayes classifier
6. Evaluate model performance
7. Save trained model and vectorizer
8. Deploy model using Streamlit

---

## 📂 Project Structure

```
Spam_Email_Classifier/

│
├── app.py                  # Streamlit application
├── train_model.py          # Model training script
├── requirements.txt        # Required libraries
├── README.md               # Project documentation
├── .gitignore              # Ignored files
│
├── dataset/
│   └── spam.csv            # Spam email dataset
│
└── model/
    ├── spam_model.pkl      # Saved ML model
    └── vectorizer.pkl      # Saved TF-IDF vectorizer
```

---

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_LINK
```

### 2. Navigate to Project Folder

```bash
cd Spam_Email_Classifier
```

### 3. Install Required Libraries

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Application

Start the Streamlit application:

```bash
python -m streamlit run app.py
```

The application will open in your browser.

---

## 📊 Machine Learning Algorithm

### Multinomial Naive Bayes

Multinomial Naive Bayes is a supervised machine learning algorithm commonly used for text classification problems.

It is effective for:

- Spam detection
- Sentiment analysis
- Document classification

---

## 🔤 Text Processing

### TF-IDF Vectorization

TF-IDF (Term Frequency-Inverse Document Frequency) converts email text into numerical values that can be understood by machine learning algorithms.

---

## 📈 Model Evaluation

The model performance is evaluated using:

- Accuracy Score
- Test Data Prediction

---

## 🖥️ Application Preview

Add screenshots of your Streamlit application here:

- Home page
- Spam email prediction
- Non-spam email prediction

---

## 🔮 Future Improvements

- Add more machine learning algorithms
- Compare different models
- Add confusion matrix visualization
- Improve text preprocessing
- Deploy application online

---

## 👩‍💻 Author

**Rabia Shahzad**

BS Information Technology Student

---

## ⭐ Project Purpose

This project was developed to understand and implement:

- Supervised Machine Learning
- Natural Language Processing
- Text Classification
- Model Deployment using Streamlit

---

⭐ If you find this project useful, consider giving it a star!
