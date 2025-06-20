
# 🏨 Hotel Booking Cancellation Prediction

> A machine learning project to predict hotel booking cancellations using customer and booking features.

## 📘 Project Overview

This project analyzes booking data from a hotel to determine whether a reservation is likely to be cancelled. Using data preprocessing, exploratory analysis, and machine learning models, we identify patterns and predict cancellations to improve hotel planning and customer experience.

---

## 🎯 Objectives

- Understand key patterns in hotel booking data.
- Identify features that influence cancellations (e.g., lead time, deposit type, customer type).
- Train and evaluate machine learning models to predict cancellations.
- Provide actionable insights for hotel management.

---

## 📊 Dataset

- **Source**: [Hotel Booking Demand Dataset](https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand)
- **Records**: Over 119,000 bookings
- **Target**: `is_canceled` (1 = Cancelled, 0 = Not Cancelled)
- **Key Features**:
  - Hotel type, Lead time, Arrival date
  - Customer type, Deposit type, Booking changes
  - Number of adults, children, and weekend nights

---

## 🔍 Exploratory Data Analysis (EDA)

- Uncovered cancellation trends based on:
  - Booking lead time
  - Deposit types
  - Market segments
- Visualizations: Count plots, histograms, heatmaps

---

## 🧠 Machine Learning Models

Models evaluated:
- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost (optional)

> Preprocessing includes handling missing values, encoding categorical variables, and scaling numerical features.

---

## 🧪 Evaluation Metrics

- Accuracy
- Precision & Recall
- F1-Score
- Confusion Matrix
- ROC Curve & AUC

---

## 🛠️ How to Run

1. Clone the repository:
```bash
git clone https://github.com/yourusername/hotel-booking-prediction.git
cd hotel-booking-prediction
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Launch the notebook:
```bash
jupyter notebook
```

---

## 📁 Files

- `Data Analytics - Hotel Booking Prediction.ipynb`: Main notebook
- `hotel_bookings.csv`: Dataset (download from Kaggle)
- `requirements.txt`: Python dependencies
- `README.md`: Project documentation

---

## 🧑‍💻 Contributors

- Your Name Here

---

## 📌 Future Improvements

- Hyperparameter tuning (e.g., GridSearchCV)
- Deployment as a web app with Streamlit
- Model explainability (e.g., SHAP, LIME)

---
