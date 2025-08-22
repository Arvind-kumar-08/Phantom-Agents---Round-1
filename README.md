# Heart Disease Prediction

This repository provides a full machine learning workflow for predicting heart disease using patient clinical data. The main notebook, `Heart-Disease-prediction-1.ipynb`, demonstrates data analysis, preprocessing, model building, and evaluation steps suitable for medical ML studies.

---

## Project Overview

Heart disease poses a major health challenge globally. Machine learning offers fast, effective risk prediction using key clinical indicators. This project leverages a dataset with 303 patient records and 14 features to develop, train, and assess ML models that predict the likelihood of heart disease.

---

## Dataset Details

The dataset covers 303 samples with these features:

| Feature    | Description                                                           |
|------------|-----------------------------------------------------------------------|
| age        | Patient age in years                                                  |
| sex        | 1 = male, 0 = female                                                  |
| cp         | Chest pain type (value 0-3)                                           |
| trestbps   | Resting blood pressure (mm Hg)                                        |
| chol       | Serum cholesterol (mg/dl)                                             |
| fbs        | Fasting blood sugar > 120 mg/dl (1 = true, 0 = false)                 |
| restecg    | Resting electrocardiographic results (0-2)                            |
| thalach    | Maximum heart rate achieved                                           |
| exang      | Exercise-induced angina (1 = yes, 0 = no)                             |
| oldpeak    | ST depression induced by exercise                                     |
| slope      | Slope of peak ST segment (0-2)                                        |
| ca         | Number of major vessels colored by fluoroscopy (0-4)                  |
| thal       | Thalassemia (1 = normal, 2 = fixed defect, 3 = reversible defect)     |
| target     | 1 = heart disease, 0 = no heart disease                               |

Sample statistics:
- Total samples: 303
- Age range: 29–77 years (mean 54.37)
- Cholesterol: 126–564 mg/dl (mean 246.26)
- Features include both categorical and continuous values

---

## Notebook Workflow

### 1. Data Loading
- Loads CSV data
- Displays data shape and column info

### 2. Data Analysis
- Descriptive statistics (mean, std, min, max, quartiles)
- Correlation matrix
- Visualization of feature distributions

### 3. Preprocessing
- Handles missing data and outliers
- Encodes categorical features
- Feature normalization/scaling as needed
- Train/test split preparation

### 4. Model Development
- Implements key algorithms:
  - Logistic Regression
  - Decision Tree & Random Forest
  - Support Vector Machine
  - K-Nearest Neighbors
- Hyperparameter tuning (optional)
- Model training and prediction

### 5. Evaluation
- Reports metrics: accuracy, precision, recall, F1-score, ROC-AUC
- Confusion matrix and classification reports
- Feature importance analysis

### 6. Visualization
- Plots feature distributions, correlations, model metrics, and feature importance graphs

---

## Quickstart

1. **Clone the Repository**
git clone <repo-url>
2. **Install Requirements**
Make sure Python 3.x is installed.

3. **Run the Notebook**
Open `Heart-Disease-prediction-1.ipynb` in [Google Colab](https://colab.research.google.com/) or Jupyter Notebook and run all cells in sequence.

4. **Customize**
- Swap or tune models in code cells
- Add visualizations for deeper insights
- Apply your own data for extended analysis

---

## Extending the Project

- Test different models or data preprocessing approaches
- Fine tune hyperparameters
- Integrate new datasets to enhance generalizability
- Add advanced visualizations and reporting

---

## Repository Structure

├── Heart-Disease-prediction-1.ipynb # Main analysis notebook
├── README.md # Project documentation
├── requirements.txt # Python dependencies
└── data/ # (optional) dataset location

---

## License

MIT License – use, modify, or redistribute without restriction.

---

## Contact

For questions, suggestions, or contributions, please open an issue or submit a pull request.

