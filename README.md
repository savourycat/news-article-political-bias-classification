# News Article Political Bias Classification

An NLP machine learning project that automatically classifies news articles by their **political bias** (Left, Center, or Right). The model uses **TF-IDF vectorization** and **Logistic Regression** to analyze article text and predict political leaning.

---

## Quick Start

1. **Clone the repository:**

   ```bash
   git clone https://github.com/savourycat/news-article-political-bias-classification.git
   cd news-article-political-bias-classification
   ```

2. **Install dependencies:**

   ```bash
   pip install scikit-learn pandas matplotlib seaborn numpy
   ```

3. **Download the dataset:**
   - Download `political_bias.csv` from [this link](https://drive.google.com/file/d/1LRA__JZbdLxGIc_UwJm-CjELR2nQG36C/view?usp=sharing)
   - Place it in the project root directory

4. **Run the notebook:**
   - Open `Political_Bias_Classification.ipynb` and run all cells

---

## Project Overview

This project applies text classification techniques to detect political bias in news articles. By training on labeled data, the model learns language patterns associated with different political viewpoints.

**Key Capabilities:**

- Text cleaning and preprocessing
- TF-IDF vectorization for feature extraction
- Logistic Regression classification
- Performance evaluation (accuracy, precision, recall, F1-score)
- Interactive predictions for custom text input

---

## How It Works

The notebook follows these steps:

1. **Load Dataset** — Import the labeled article data
2. **Preprocess Text** — Clean and normalize article text
3. **Split Data** — Create training and testing sets
4. **Vectorize** — Convert text to TF-IDF features
5. **Train Model** — Train Logistic Regression classifier
6. **Evaluate** — Generate accuracy, precision, recall, and confusion matrix
7. **Predict** — Test the model with custom political statements

---

## Technologies

- Python 3.x
- pandas — data manipulation
- scikit-learn — machine learning
- matplotlib — visualization
- seaborn — enhanced visualizations
- numpy — numerical computing

---

## Model Performance

- **Accuracy:** ~85–95% (varies by dataset)
- **Metrics:** Precision, Recall, F1-score per class
- **Visualization:** Confusion matrix heatmap

---

## Interactive Prediction

After training, test your own political statements:

```
Enter a political statement (or type 'exit' to quit):
> The government should increase social welfare programs.
Predicted Bias: Left
```

---

## Output Files

The notebook generates the following files:

- `classification_report.csv` — detailed model performance metrics
- `confusion_matrix.png` — visual confusion matrix heatmap
