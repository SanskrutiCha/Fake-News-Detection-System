# 📰 Fake News Detection System

This project is a machine learning-based system that detects **fake news** using natural language processing (NLP) and classification algorithms. It is trained on labeled datasets of real and fake news articles and can predict whether a new article is **true or fake** based on its content.

---

## 💡 Key Features

- ✅ Detects fake or real news based on the input text
- 📊 Trained on real-world datasets (`True.csv` and `fake.csv`)
- 🧠 Uses NLP for text preprocessing
- 🛠 Built using Python, Scikit-learn, Pandas, and Jupyter Notebook
- 💾 Model saved with `model.pkl` and `vectorizer.pkl`
- 🧪 Includes Jupyter Notebook for training and testing
- 🌐 (Optional) Deployable via Flask or Streamlit for web use

---

## 🧰 Tech Stack

- Python
- Scikit-learn
- Pandas
- NumPy
- NLTK / re
- Jupyter Notebook
- Pickle (`model.pkl`, `vectorizer.pkl`)

---

## 📁 Project Structure
project/
│
├── fake_news.ipynb        # Main notebook for training & testing
├── model.pkl              # Trained classification model
├── vectorizer.pkl         # TF-IDF Vectorizer
├── README.md              # You're reading it!
├── fake.csv               # Fake news dataset (add manually)
└── True.csv               # Real news dataset (add manually)
Note: True.csv and fake.csv are not included in this repository due to their large size.
Please download and add them manually to the project directory before running the notebook.


---

## ⚙️ How It Works

1. **Data Collection**: `True.csv` and `fake.csv` datasets are combined and labeled.
2. **Preprocessing**: Text is cleaned (lowercased, punctuations removed, stopwords removed).
3. **Feature Extraction**: TF-IDF vectorizer converts text to numerical vectors.
4. **Model Training**: A classification algorithm (like Logistic Regression or PassiveAggressiveClassifier) is trained.
5. **Prediction**: New text input is classified as "FAKE" or "REAL".

---

## 🚀 Usage

### 🧪 Jupyter Notebook

Run the notebook:

```bash
jupyter notebook fake_news.ipynb
