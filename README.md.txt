# AI-Powered Social Media Intelligence Platform

An end-to-end multi-modal deep learning system designed to analyze, process, and predict social media trends, user behavior, and content safety across multiple submodules.

---

## 🚀 Project Overview
This platform integrates five specialized deep learning models built using TensorFlow and Keras to tackle different aspects of social media analytics:
1. **Sentiment Analysis (SimpleRNN):** Classifies user text comments into positive, negative, or neutral sentiments.
2. **Fake News Classification (RNN):** Detects whether a given news snippet or post is real or fake.
3. **Toxic Comment Detection (Bidirectional LSTM):** Identifies harmful, toxic, or abusive language in social media posts.
4. **Image Content Classification (CNN):** Categorizes uploaded social media images into distinct visual classes (e.g., photos, memes, graphics, screenshots).
5. **Trend & Engagement Prediction (Stacked LSTM):** Time-series model predicting future engagement scores based on historical interaction metrics.

---

## 🛠️ Tech Stack & Requirements
* **Python** (3.8+)
* **TensorFlow / Keras**
* **NumPy & Matplotlib**
* **JupyterLab / Jupyter Notebook**

To install required dependencies:
```bash
pip install -r requirements.txt