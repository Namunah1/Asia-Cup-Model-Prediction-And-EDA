
---

# 🏏 Asia Cup Cricket Match Prediction & EDA

This project focuses on **Exploratory Data Analysis (EDA)** and **Machine Learning models** for predicting outcomes of Asia Cup cricket matches (1984–2022). Using historical match data, we explore insights and train models to predict match winners.

---

## 📂 Dataset

* **Source:** [Asia Cup Cricket Dataset (1984–2022) – Kaggle](https://www.kaggle.com/datasets/hasibalmuzdadid/asia-cup-cricket-1984-to-2022/data)
* Contains match-level information such as teams, scores, venues, and results.

---

## 🔎 Exploratory Data Analysis (EDA)

Key analyses performed:

* Team performance trends across years.
* Win/loss ratios of participating countries.
* Venue-wise match outcomes.
* Toss impact on results.
* Visualization of historical patterns.

---

## 🤖 Machine Learning Models Implemented

Two supervised learning models were trained to predict match winners:

1. **Random Forest Classifier** 🌲

   * Robust ensemble method.
   * Handles categorical + numerical features well.
   * Useful for feature importance ranking.

2. **XGBoost Classifier** ⚡

   * Gradient boosting algorithm optimized for performance.
   * Provides better accuracy on imbalanced datasets.
   * Handles non-linear relationships effectively.

---

## 📊 Pipeline

1. **Data Preprocessing**

   * Cleaning missing values.
   * Encoding categorical features (teams, venues).
   * Train-test split for evaluation.

2. **Model Training**

   * Trained Random Forest & XGBoost on processed dataset.
   * Hyperparameter tuning for better accuracy.

3. **Evaluation Metrics**

   * Accuracy
   * Precision, Recall, F1-Score
   * Confusion Matrix

---

## 🚀 Results

* Both models show promising accuracy for predicting match winners.
* XGBoost slightly outperforms Random Forest in terms of precision and recall.
* Insights from feature importance help understand match-winning factors (e.g., toss, team strength, venue).

---

## 🛠️ Technologies Used

* **Python**
* **Pandas, NumPy** – Data processing
* **Matplotlib, Seaborn** – Visualization
* **Scikit-learn** – Machine learning utilities
* **XGBoost** – Gradient boosting algorithm

---

## 📌 Future Work

* Extend dataset with player-level stats for deeper insights.
* Implement deep learning models (e.g., Neural Networks).
* Build a web app for interactive match prediction.

---

## 📜 How to Run

1. Clone this repo:

   ```bash
   git clone https://github.com/your-username/Asia-Cup-Model-Prediction-And-EDA.git
   cd Asia-Cup-Model-Prediction-And-EDA
   ```

2. Run the notebook/script for EDA and model training.

---

## 🙌 Acknowledgments

* Dataset provided by [Hasib Al Muzdadid](https://www.kaggle.com/datasets/hasibalmuzdadid/asia-cup-cricket-1984-to-2022).
* Inspiration from cricket analytics and sports ML projects.

---
