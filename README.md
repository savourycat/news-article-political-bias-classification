# News Article Political Bias Classification

A **Natural Language Processing (NLP)** machine learning project that classifies news articles by their **political bias** (e.g., *Left*, *Center*, *Right*).  
It uses **TF-IDF vectorization** and a **Logistic Regression** classifier to analyze article text and predict its political leaning.

---

## 📘 Project Overview

This project applies **text classification** techniques to detect the political bias of news articles.  
By training on labeled article data, the model learns patterns in language that correspond to political leanings.

**Main features:**
- Cleans and preprocesses raw text data  
- Transforms text using **TF-IDF Vectorization**  
- Trains a **Logistic Regression** classifier  
- Evaluates model performance with **accuracy**, **classification report**, and **confusion matrix**  
- Supports **interactive predictions** for custom user input  

---

## 🧠 Technologies Used

- Python 3.x  
- pandas  
- scikit-learn  
- seaborn  
- matplotlib  
- numpy  

---

## ⚙️ Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/swathidotdev/News-Article-Political-Bias-Classification.git
   cd News-Article-Political-Bias-Classification

2. Install dependencies:
   ```bash
   pip install scikit-learn pandas matplotlib seaborn

3. Dataset
Due to file-size limits, the full dataset is hosted externally:  
👉 [Download political_bias.csv](https://drive.google.com/file/d/1LRA__JZbdLxGIc_UwJm-CjELR2nQG36C/view?usp=sharing)

Place it in the project root before running the notebook.

---
## The notebook steps:
- Load dataset
- Clean and preprocess data
- Train/test split
- Train model (TF-IDF + Logistic Regression)
- Evaluate model
- Predict custom political statements

---
## Example Output
- Accuracy: ~85–95% (depending on dataset)
- Metrics: Precision, Recall, F1-score
- Visualization: Confusion Matrix heatmap

---
## Interactive Prediction
You can test your own political statement in the notebook:
   ```bash
   Enter a political statement (or type 'exit' to quit):
   > The government should increase social welfare programs.
   Predicted Bias: Left
```
---
## 📊 Outputs
After training, the notebook saves:
- classification_report.csv — model performance metrics
- confusion_matrix.png — visual confusion matrix
