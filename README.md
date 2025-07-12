# 🏠 Real Estate Market Intelligence System

A complete data science pipeline to analyze, predict, segment, and recommend real estate properties based on customer preferences and market patterns.

---

## 🎯 Objectives

- 🧠 Predict property prices using machine learning regression models.
- 👥 Classify potential customers as interested or not.
- 📊 Segment customers and properties using clustering (KMeans + PCA).
- 🤖 Recommend properties to users using both rule-based and deep learning recommendation systems.
- 🧩 Visualize key patterns and features for business insight and decision support.

---

## 📁 Dataset Information

### Main Datasets:

- `Real estate.csv`: Property data (`location`, `area`, `bedrooms`, `bathrooms`, `property_type`, `price`)
- `Leads.csv`: Customer data (`age`, `income`, `job`, `preferences`, `interested`)

### Sources:

- 📦 Property dataset from [Kaggle](https://www.kaggle.com/datasets/saurabhshahane/real-estate-price-prediction)
- 📦 Leads data (synthetic or anonymized)

---

## ⚙️ Techniques Used

| Component            | Method / Library                  |
|---------------------|------------------------------------|
| Data Cleaning        | Pandas, LabelEncoder              |
| Visualization        | Matplotlib, Seaborn               |
| Price Prediction     | LinearRegression, MAE, R²         |
| Customer Classification | RandomForestClassifier        |
| Clustering           | KMeans, PCA                       |
| Recommendation       | Cosine Similarity, TensorFlow NN  |
| Exporting Results    | CSV export (cleaned + predicted)  |

---

## 📈 Model Evaluation

| Task                   | Model               | Metric          | Score  |
|------------------------|---------------------|------------------|--------|
| Price Prediction       | Linear Regression   | R² Score         | ~0.82  |
| Customer Classification| Random Forest       | F1-Score         | ~0.91  |
| Property Recommendation| Deep Neural Network | Accuracy / AUC   | ~0.87  |

---

## 🔍 Key Visualizations

- Distribution of property prices
- Relationship between area and price
- Boxplot by property type
- Clustering visualization via PCA
- Confusion matrix for customer prediction
- ROC curve for classification

---

## 💡 Improvements & Extensions

- 🗺️ Add map-based visualization using Folium
- 🎛️ Build a Streamlit or Dash dashboard
- 🔍 Use SHAP for explainability of predictions
- 📌 Real-time user-based recommendation system
- 🏗️ Connect with real property APIs for real-world data

---

## 🛠️ How to Run

1. Clone the repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
