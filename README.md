# 📰 AI Misinformation & Fake News Detector

An NLP-powered text analysis system built with **Python** and **scikit-learn** that analyzes news content to determine if it is authentic or simulated misinformation. The model utilizes a TF-IDF vectorizer paired with a Logistic Regression classifier, complete with a clean web interface powered by **Gradio**.

## 🚀 Features
* **Text Processing Pipeline:** Strips common stop-words and uses statistical word frequencies to extract linguistic patterns common in fake news.
* **Gradio Web Interface:** Provides a simple textbox UI where users can paste articles and get real-time reliability score estimates.
* **Standalone Deployment:** Fully cloud-compatible execution designed to be run immediately via Google Colab.

## 🛠️ Tech Stack
* Python 3
* Scikit-Learn (TF-IDF Vectorization & Classification)
* Gradio (Web Dashboard UI)
* Pandas & Joblib

## 💻 How to Use
1. Open a new notebook on [Google Colab](https://colab.research.google.com/).
2. Paste and run the training block to pull down the corpus dataset, train the weights, and export the `.pkl` files.
3. Execute the Gradio app cell block to launch a live public link you can share with friends to test real-world headlines!

---
### Suggested GitHub Tags
`nlp` • `machine-learning` • `fake-news-detection` • `gradio` • `text-classification` • `scikit-learn`
