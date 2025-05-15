# US Accidents Severity Prediction

This project explores and models the severity of traffic accidents in the United States using real-world data from the [US Accidents Dataset](https://www.kaggle.com/sobhanmoosavi/us-accidents).

## 🚗 Objective

To classify accident severity (on a scale of 1 to 4) using a variety of machine learning models, and compare their performance based on accuracy and F1-score.

## 📊 Dataset

- 1.5M+ accident records (2016–2021)
- Features include location, weather, time, and road conditions

## 🧹 Workflow

1. **Exploratory Data Analysis (EDA)**
2. **Preprocessing**: Missing value handling, label encoding, scaling
3. **Modeling**:
   - Support Vector Machine (SVM)
   - Decision Tree
   - Random Forest
   - K-Nearest Neighbors (KNN)
   - Artificial Neural Network (ANN)
4. **Evaluation**: Accuracy, F1-score, confusion matrix

## 🧠 Results

- Random Forest showed the best overall performance.
- Accuracy and F1 scores were calculated to compare models.
- The pipeline supports easy extension to include more features or tuning.

## 🛠️ Tools & Technologies

- Python, Scikit-learn, Pandas, NumPy
- Jupyter Notebook
- Matplotlib / Seaborn (for visualization – optional)

## 📈 Future Improvements

- Add feature importance analysis
- Include hyperparameter tuning (GridSearchCV)
- Improve data visualizations for better EDA
- Add SHAP for model explainability

