# 🧠 Twitter Sentiment Analysis using Neural Network

This project uses a Neural Network model built with TensorFlow and Keras to classify tweets into **positive** or **negative** sentiments. The model was trained and evaluated using real-world Twitter data.

---

## 🔍 Problem Statement

Social media platforms like Twitter are full of opinions. Understanding user sentiment can be crucial for brands, campaigns, or public analysis. This project aims to classify tweet sentiment into:

- ✅ Positive
- ❌ Negative

---

## 🛠️ Technologies Used

- Python
- TensorFlow / Keras
- NumPy, Pandas
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

---

## 📊 Model Overview

- **Model Type:** Sequential Neural Network
- **Loss Function:** Binary Crossentropy
- **Optimizer:** RMSprop
- **Activation Functions:** LSTM + Sigmoid
- **Validation Split:** 10%
- **Accuracy:** ~75%

---

## 📈 Evaluation

### ✅ Confusion Matrix:
- **4509** negative tweets correctly classified  
- **4439** positive tweets correctly classified

### 📉 ROC Curve:
- **AUC Score:** 0.75  
- Indicates a fair performance for binary classification

<p align="center">
  <img src="confusion_matrix.png" alt="Confusion Matrix" width="400"/>
  <img src="roc_curve.png" alt="ROC Curve" width="400"/>
</p>

---

## 🧪 How to Run

1. Clone the repository:
```bash
git clone https://github.com/yourusername/twitter-sentiment-nn.git

Install the requirements:

bash
pip install -r requirements.txt
Run the notebook or Python script:

bash
jupyter notebook sentiment_analysis.ipynb

🙋‍♂️ About Me
I’m Shahidul Islam, an aspiring Data Scientist from Bangladesh, passionate about building intelligent systems and sharing my journey.

Connect with me:

📷 Instagram: https://www.instagram.com/shahiddatascientist/


