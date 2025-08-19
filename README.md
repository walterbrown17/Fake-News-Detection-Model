# Fake-News-Detection-Model
This repository describes the basic workflow for working with text data
# 📰 Fake News Detection using Machine Learning

This project demonstrates how Machine Learning can be used to classify news articles as **Real ✅** or **Fake ❌** using Natural Language Processing (NLP).

---

## 🚀 Try it Yourself in Google Colab
Click the link below to open and run the notebook directly in your browser:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]([https://colab.research.google.com/github/your-username/Fake-News-Detection-ML/blob/main/Fake_News_Detection.ipynb])

---

## 📊 Project Workflow

1. **Import Libraries**  
   We use `pandas`, `numpy`, `sklearn`, and `nltk` for text preprocessing, vectorization, and classification.

2. **Load Dataset**  
   - `fake.csv` → contains fake news samples  
   - `true.csv` → contains true news samples  
   Both datasets are labeled and combined into a single dataframe.

3. **Preprocessing**  
   - Cleaning text (removing punctuation, numbers, special characters).  
   - Converting to lowercase.  
   - Removing stopwords.  
   - Applying **stemming** and **lemmatization**.  

4. **Vectorization**  
   - **Bag of Words (BoW)** – simple word frequency representation.  
   - **TF-IDF (Term Frequency – Inverse Document Frequency)** – highlights important words while reducing weight of common words.

5. **Model Training**  
   - Classifier: **Logistic Regression**  
   - Train/Test split applied (80% / 20%).  
   - Models trained using both BoW and TF-IDF features.

6. **Evaluation**  
   - Accuracy Score  
   - Confusion Matrix  
   - Classification Report  

7. **Prediction Demo**  
   Enter a news headline/article and see whether the model predicts it as **Fake ❌** or **Real ✅**.

---

## 📈 Results

- **Bag of Words Model** → ~XX% Accuracy  
- **TF-IDF Model** → ~XX% Accuracy  

*(Update with your actual accuracy results.)*

---

## 📂 Dataset

The dataset (`fake.csv` and `true.csv`) is provided in the `data/` folder.  

Source: [Kaggle Fake News Dataset](https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset)

---

## 💡 Key Takeaways

- Data preprocessing is crucial in NLP projects.  
- Bag of Words is simple but often effective.  
- TF-IDF usually gives better generalization.  
- ML models can only perform well if the training data is **balanced** and **represents the real-world use case**.

---

## 👨‍💻 Author
This project was created for a **guest lecture on Machine Learning and NLP** to help students understand the practical workflow of building an ML model from scratch.

