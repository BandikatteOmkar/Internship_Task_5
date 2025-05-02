# Internship_Task_5

# Heart Disease Prediction 

This Jupyter Notebook focuses on analyzing and predicting heart disease using machine learning techniques. The dataset includes various health-related parameters of patients, and the goal is to classify whether or not a patient has heart disease.

## 📁 Dataset

The dataset used is `heart.csv`, which includes the following features:

- Age
- Sex
- Chest pain type (cp)
- Resting blood pressure (trestbps)
- Serum cholesterol (chol)
- Fasting blood sugar (fbs)
- Resting ECG results (restecg)
- Maximum heart rate achieved (thalach)
- Exercise-induced angina (exang)
- ST depression induced by exercise (oldpeak)
- Slope of the peak exercise ST segment (slope)
- Number of major vessels colored by fluoroscopy (ca)
- Thalassemia (thal)
- Target (presence of heart disease)

## 🧰 Libraries Used

- `pandas`, `numpy` – for data manipulation
- `matplotlib`, `seaborn` – for data visualization
- `scikit-learn` – for machine learning models and evaluation

## 📊 Exploratory Data Analysis (EDA)

The notebook includes the following EDA steps:

- Reading and displaying the dataset
- Checking dataset shape and column info
- Identifying null values
- Statistical summary of features
- Visualizing:
  - Histograms
  - Boxplots
  - Correlation heatmap
  - Count plots for categorical features

## 🧠 Machine Learning Models

The following classification models are implemented and evaluated:

- Decision Tree Classifier
- Random Forest Classifier

### 📈 Evaluation Metrics

Each model is evaluated using:

- Accuracy Score
  
## ✅ Results

At the end of the notebook, the models are compared based on accuracy to identify the best-performing model.

## 📌 Conclusion

This notebook demonstrates the application of multiple classification algorithms for medical data and highlights the importance of model evaluation in selecting the best predictive model.
