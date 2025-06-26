# Movie-Review-Analyzer 🎬

A Machine Learning model to automatically analyze and classify the sentiment of movie reviews, complete with an **interactive** demo for *real-time* testing.

---

## 🚀 Interactive Demo

This model isn't just code—it’s ready to be tried out! Below is a preview of the demo interface when the application is launched via notebook.

![Demo Aplikasi Movie Review Analyzer](https://github.com/nfldffa/Movie-Review-Analyzer/blob/main/demo-movie.png)




---

## 🎯 Project Challenge & Objectives

In the digital era, text data like reviews, comments, and tweets are overflowing. The challenge is how machines can understand the subjective meaning behind these texts.

The objectives of this project are:
1.  To build an accurate text classification model using NLP techniques.
2.  To demonstrate the end-to-end process of a Machine Learning project, from data cleaning to simple model deployment.
3.  To create an interactive tool that allows users to test the model’s performance directly.
   
## ✨ Skills Demonstrated

This project showcases expertise in:
- **Natural Language Processing (NLP) Text Classification:** Applying algorithms to understand and categorize unstructured text.
- **Text Data Preprocessing:** Cleaning and preparing raw text data (HTML tags, stopwords, punctuation) for modeling.
- **Feature Engineering:** Using TF-IDF to convert text into machine-readable numeric features.
- **Model Evaluation:** Measuring model performance quantitatively with metrics like Accuracy and F1-Score.
- **Rapid Prototyping:** Building a functional user interface (UI) using Gradio to showcase the model results.

## 🛠️ Tech Stack & Library

| Technology | Purpose |
| :--- | :--- |
| **Python** | 	Main programming language |
| **Pandas** | Data manipulation & cleaning |
| **NLTK** | Text preprocessing & stopword handling |
| **Scikit-learn** | Feature engineering (TF-IDF) & modeling (Logistic Regression) |
| **Gradio** | 	Building the interactive demo UI |
| **Matplotlib & Seaborn**| Data visualization (EDA) |
| **Google Colab** | Cloud-based development environment |

## 📈 Model Results & Performance

After training and validation, the model achieved an accuracy of 87.38% on the test dataset. This indicates a strong ability to distinguish between positive and negative reviews.

<details>
<summary>Click to view the Detailed Classification Report</summary>

```
Laporan Klasifikasi:
              precision    recall  f1-score   support

    Negative       0.88      0.87      0.87      4961
    Positive       0.87      0.88      0.88      5039

    accuracy                           0.87     10000
   macro avg       0.87      0.87      0.87     10000
weighted avg       0.87      0.87      0.87     10000
```
