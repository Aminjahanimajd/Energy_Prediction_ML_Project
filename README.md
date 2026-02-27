# Energy Prediction ML Project

## 📋 Project Overview

This project applies machine learning techniques to predict household appliance energy consumption. Using comprehensive exploratory data analysis (EDA) and statistical modeling, we aim to understand the patterns of energy usage and build predictive models to forecast future consumption.

**Target Variable:** Appliances energy consumption (in Wh) measured over 10-minute intervals

---

## 📊 Dataset

**Dataset Name:** Appliances Energy Prediction Dataset  
**Source:** energydata_complete.csv  
**Records:** 19,735 observations  
**Features:** Multiple environmental and temporal variables including:
- Energy consumption metrics (target: Appliances)
- Temperature readings from different rooms
- Humidity levels
- Visibility and pressure measurements
- Date and time information

### Dataset Characteristics
- **Right-skewed distribution** in the target variable
- **Heteroscedasticity** present in energy consumption patterns
- **No missing values** - complete dataset ready for analysis
- **10-minute sampling intervals** providing high temporal resolution

---

## 🎯 Project Objectives

1. **Exploratory Data Analysis (EDA)**
   - Understand data structure and distributions
   - Identify relationships between features and target variable
   - Detect outliers and data anomalies

2. **Feature Engineering**
   - Create temporal features (hour, day, season)
   - Develop interaction terms
   - Apply transformations for improved model performance

3. **Model Development**
   - Evaluate linear regression models
   - Implement nonlinear approaches for better fit
   - Consider ensemble methods for improved predictions

4. **Model Evaluation**
   - Assess performance using appropriate metrics (MAE, RMSE, R²)
   - Cross-validation and hyperparameter tuning
   - Provide actionable insights on energy consumption patterns

---

## 📁 Project Structure

```
Energy_Prediction_ML_Project/
├── Energy_Prediction.ipynb              # Main analysis and modeling notebook
├── energydata_complete.csv              # Complete dataset
├── ML_Workflow.pdf                      # Project methodology documentation
├── ML_Workflow.docx                     # Detailed workflow document
├── README.md                            # This file
└── Professor-G-Fiumara-Machine-Learning-Course.pptx  # Course reference materials
```

---

## 🛠️ Technology Stack

- **Python 3.x**
- **Data Processing:** Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn
- **Statistical Analysis:** SciPy
- **Machine Learning:** Scikit-learn (recommended for modeling phase)

---

## 📝 Notebook Contents

### Energy_Prediction.ipynb

The main Jupyter notebook contains:

1. **Data Loading & Imports**
   - Essential libraries setup
   - Dataset loading and initial exploration

2. **Dataset Overview**
   - Shape and structure analysis
   - Data type verification
   - Missing value assessment
   - Summary statistics

3. **Target Variable Analysis**
   - Distribution analysis (histogram, boxplot)
   - Skewness and outlier detection
   - Statistical properties

4. **Exploratory Data Analysis**
   - Feature distributions
   - Correlation analysis
   - Temporal patterns
   - Feature relationships with target variable

---

## 🚀 Getting Started

### Prerequisites
```bash
pip install pandas numpy matplotlib seaborn scipy scikit-learn jupyter
```

### Running the Analysis

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/Energy_Prediction_ML_Project.git
   cd Energy_Prediction_ML_Project
   ```

2. **Launch Jupyter Notebook:**
   ```bash
   jupyter notebook Energy_Prediction.ipynb
   ```

3. **Execute cells sequentially** to reproduce the analysis

---

## 📈 Key Findings

- Energy consumption shows **right-skewed distribution** with concentration at lower values
- Presence of occasional **high-consumption peaks** suggests distinct usage patterns
- **Temporal and environmental factors** are significant predictors
- Nonlinear models likely outperform linear approaches due to heteroscedasticity
- Logarithmic transformation may improve model assumptions

---

## 💡 Recommendations

1. **Feature Engineering:** Create temporal features (hour of day, day of week, season)
2. **Dimensionality Reduction:** Consider PCA for correlated features
3. **Model Selection:** Test ensemble methods (Random Forest, Gradient Boosting)
4. **Data Transformation:** Apply log transformation to target variable
5. **Hyperparameter Tuning:** Use GridSearchCV for optimal parameters
6. **Cross-Validation:** Implement k-fold CV for robust evaluation

---

## 📚 References

- **Course:** Professor G. Fiumara's Machine Learning Course
- **Dataset Citation:** Appliances Energy Prediction Dataset (UCI Machine Learning Repository)
- **Methodology:** Standard ML pipeline with emphasis on EDA and feature engineering

---

## 👤 Author

**Student Project**  
Bachelor's Degree, Semester 5  
Machine Learning Course  
Date: 2026

---

## 📄 License

This project is provided for educational purposes as part of the Machine Learning course curriculum.

---

## 🤝 Contributing

This is an academic project. For improvements or suggestions, please refer to course instructors.

---

**Last Updated:** February 27, 2026  
**Status:** Active Development
