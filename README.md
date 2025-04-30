# 🌾 Crop Recommendation System using Machine Learning

This project aims to recommend the most suitable crop to cultivate based on soil nutrients and environmental conditions using a Random Forest Classifier.

---

## 📁 File Structure

```
├── analysis.ipynb              # Main notebook containing all analysis, visualizations, and model training
├── Crop_recommendation.csv     # Dataset used for training and evaluation
├── random_forest_model.pkl     # Saved Random Forest model for future predictions
```

---

## 📊 Dataset Information

- **Dataset Source**: [Crop Recommendation Dataset (Kaggle)](https://www.kaggle.com/datasets/atharvaingle/crop-recommendation-dataset)
- **Description**: The dataset contains the following features:
  - `N`: Nitrogen content in soil
  - `P`: Phosphorus content in soil
  - `K`: Potassium content in soil
  - `temperature`: Temperature in °C
  - `humidity`: Relative humidity in %
  - `ph`: pH value of the soil
  - `rainfall`: Rainfall in mm
  - `label`: The crop that can be grown

---

## ✅ Model Performance

- **Model Used**: Random Forest Classifier
- **Accuracy Achieved**: **99.31%**
- **No Feature Scaling** was required due to the tree-based nature of the model.
- The model performs exceptionally well in predicting the correct crop based on environmental inputs.

---

## 📌 How to Use

1. Open `analysis.ipynb` in Jupyter Notebook or Google Colab.
2. Run through the notebook to explore:
   - Exploratory Data Analysis (EDA)
   - Label-wise feature distribution
   - Correlation insights
   - Model training and evaluation
3. You can also load the trained model from `random_forest_model.pkl` for making predictions.

---

## 📖 Full Analysis

To understand feature patterns, relationships, and how the model was trained and evaluated, **please read the notebook `analysis.ipynb`**.

---

## 👤 Author

**Yahan Madhuhansa**
