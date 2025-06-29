#  Spam Mail Detection using Machine Learning

This project is a simple implementation of a spam mail classifier using **Logistic Regression**. It uses **TF-IDF Vectorization** to convert email text into numerical features and then trains a model to classify emails as **Spam** or **Ham (not spam)**.

---

## 🔁 Workflow
![Alt Text]()

### ✅ Data Preprocessing
- Loaded dataset using `pandas`
- Replaced `NaN` values with empty strings
- Label encoding:
  - `spam` → `0`
  - `ham` → `1`

### ✂️ Train-Test Split
- Split into **training (80%)** and **testing (20%)** sets using `train_test_split`

### 🧠 Feature Extraction
- Used `TfidfVectorizer` with English stop words
- Converted messages into feature vectors

### 🤖 Model Training
- Trained a `LogisticRegression` model on the training data

### 📈 Evaluation
- Accuracy on **training data**: `96.70%`
- Accuracy on **test data**: `96.90%`

---

## 🚀 How to Run

1. Clone the repo:

   ```bash
   git clone https://github.com/PragnyasuSethi/Spam_Mail_Detection
   cd SpamMail
