# 🛡️ Spam Detection System

A robust **Spam Detection Form** built with **Python**, **Flask**, and **Machine Learning** that classifies user-submitted text messages as **Spam** or **Legitimate (Ham)**. The application utilizes a **Majority Voting Ensemble Learning** approach by combining three different machine learning models to improve prediction accuracy and reliability.

> **Smarter spam detection through ensemble machine learning.**

---

# ✨ Features

- 📝 Detect spam messages in real time
- 🤖 Ensemble Machine Learning Model
- 🗳️ Majority Voting Classification
- 🧠 Natural Language Processing (NLP)
- 📊 Individual Model Predictions
- ✅ Final Majority-Voted Prediction
- ⚡ Fast and accurate text classification
- 🌐 Flask-based web application
- 📱 Responsive user interface
- 🔒 Lightweight and easy to deploy

---

# 🛠️ Tech Stack

## Backend

- Python 3.x
- Flask

## Machine Learning

- Scikit-learn
- Ensemble Learning
- TF-IDF Vectorization

## Models Used

- Naive Bayes
- Logistic Regression
- Random Forest

## Data Processing

- Pandas
- NumPy
- Regular Expressions (Regex)

## Frontend

- HTML5
- CSS3
- Bootstrap 5
- JavaScript
- Jinja2 Templates

---

# 📚 Main Libraries Used

| Library | Purpose |
|----------|---------|
| **Flask** | Web framework |
| **Scikit-learn** | Machine Learning algorithms |
| **TF-IDF Vectorizer** | Text feature extraction |
| **Pandas** | Data processing |
| **NumPy** | Numerical computation |
| **NLTK** *(Optional)* | Stopword removal and NLP |
| **Regex** | Text cleaning |
| **Joblib / Pickle** | Model serialization |

---

# 📂 Project Structure

```text
Spam-Detection-Form/
│
├── app.py
├── requirements.txt
├── README.md
│
├── models/
│   └── models/
│       ├── naive_bayes.pkl
│       ├── logistic_regression.pkl
│       ├── random_forest.pkl
│       ├── tfidf_vectorizer.pkl
│       └── ...
│
├── templates/
│   ├── home.html
│   ├── form.html
│   ├── result.html
│   ├── about.html
│   └── contact.html
│
├── static/
│   ├── css/
│   ├── js/
│   └── images/
│
└── ...
```

---

# 🚀 Features Overview

- 📩 Spam Message Detection
- 🗳️ Majority Voting Ensemble
- 🤖 Three Machine Learning Models
- 🧠 Natural Language Processing
- 📊 Individual Model Results
- ✅ Final Prediction
- 🌐 Flask Web Interface
- 📱 Responsive Design
- ⚡ Fast Classification
- 🔒 Secure Processing

---

# ⚙️ Installation

## 1. Clone the Repository

```bash
git clone https://github.com/subham-paul/Spam-Detection-Form.git
```

```bash
cd Spam-Detection-Form
```

---

## 2. Create a Virtual Environment

### Windows

```bash
python -m venv venv
```

Activate

```bash
venv\Scripts\activate
```

### Linux / macOS

```bash
python3 -m venv venv
```

Activate

```bash
source venv/bin/activate
```

---

## 3. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 4. Run the Application

```bash
python app.py
```

or

```bash
flask run
```

---

# 🌐 Open in Browser

```
http://127.0.0.1:5000
```

---

# ⚙️ How It Works

### Step 1 — User Input

The user enters a text message into the spam detection form.

---

### Step 2 — Text Preprocessing

The application cleans the input by:

- Converting text to lowercase
- Removing special characters
- Removing punctuation
- Eliminating stopwords
- Normalizing the text

---

### Step 3 — TF-IDF Vectorization

The cleaned text is converted into numerical feature vectors using a **TF-IDF Vectorizer**, enabling machine learning models to process textual information.

---

### Step 4 — Ensemble Classification

The processed text is passed to **three independently trained machine learning models**:

- 📘 Naive Bayes
- 📙 Logistic Regression
- 📗 Random Forest

Each model predicts whether the message is:

- Spam
- Legitimate (Ham)

---

### Step 5 — Majority Voting

The application applies a **Majority Voting** strategy.

If at least **two out of three models** predict the same class, that becomes the final result.

Example:

| Model | Prediction |
|-------|------------|
| Naive Bayes | Spam |
| Logistic Regression | Spam |
| Random Forest | Not Spam |

✅ Final Result → **Spam**

---

### Step 6 — Display Results

The application displays:

- Individual predictions from each model
- Final Majority Voting prediction
- Classification result on the web interface

---

# 🧠 Machine Learning Workflow

```text
User Message
      │
      ▼
Text Cleaning
      │
      ▼
Stopword Removal
      │
      ▼
TF-IDF Vectorization
      │
      ▼
 ┌───────────────┬────────────────────┬──────────────────┐
 │               │                    │                  │
 ▼               ▼                    ▼
Naive Bayes   Logistic Regression   Random Forest
 │               │                    │
 └───────────────┴────────────────────┘
                │
                ▼
       Majority Voting
                │
                ▼
      Final Spam Prediction
```

---

# 📊 Applications

- 📧 Email Spam Detection
- 📱 SMS Spam Filtering
- 💬 Chat Moderation
- 🏢 Business Communication Security
- 🤖 AI Chat Systems
- 🔒 Cybersecurity Solutions
- 📚 NLP Learning Projects
- 🎓 Machine Learning Demonstrations

---

# 🚀 Future Enhancements

- 🧠 Transformer-Based Models (BERT/RoBERTa)
- 🌍 Multi-language Spam Detection
- 📂 Batch Message Classification
- 📈 Confidence Score Visualization
- 📊 Analytics Dashboard
- 👤 User Authentication
- 📧 Email Integration
- ☁️ Cloud Deployment
- 📱 Mobile-Friendly Interface
- 🔔 Real-Time Spam Monitoring

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository.

2. Create a feature branch.

```bash
git checkout -b feature/NewFeature
```

3. Commit your changes.

```bash
git commit -m "Add New Feature"
```

4. Push your changes.

```bash
git push origin feature/NewFeature
```

5. Open a Pull Request.

---

# 🐞 Reporting Issues

Found a bug or have a feature request?

Please open an issue with detailed information.

---

# 📜 License

This project is licensed under the **MIT License**.

---

# 👨‍💻 Author

## **Subham Paul**

Passionate about **Artificial Intelligence, Machine Learning, Natural Language Processing, Python, Flask, Cybersecurity, and Web Development.**

- GitHub: https://github.com/subham-paul
- LinkedIn: https://www.linkedin.com/in/subham-paul-india/

---

# ⭐ Show Your Support

If you found this project helpful:

- ⭐ Star this repository
- 🍴 Fork the repository
- 🤝 Contribute
- 💬 Share your feedback

---

## 🙏 Acknowledgements

Special thanks to the open-source communities behind:

- Python
- Flask
- Scikit-learn
- Pandas
- NumPy
- NLTK
- Bootstrap

for providing the technologies that made this project possible.

---

> **"Combining the intelligence of multiple machine learning models to deliver reliable and accurate spam detection."** 🛡️🤖📩
