# ObesityTrend-LinearRegression 📊

## 🎯 Project Overview

This project implements **linear regression analysis** to predict population-level obesity rates using behavioral and lifestyle factors from the CDC's Nutrition, Physical Activity, and Obesity dataset. The model analyzes relationships between dietary patterns, physical activity levels, and obesity trends across different demographics and geographic regions.

**🎯 Objective**: Predict obesity rates (% of adults with BMI ≥30) based on behavioral proxies to provide insights into public health trends and lifestyle correlations.

## 🔬 Methodology

### Linear Regression for Obesity Trend Prediction

- **Algorithm**: Linear Regression using scikit-learn
- **Approach**: Population-level modeling (not for individual predictions)
- **Target Variable**: Obesity rate percentage
- **Features**: Behavioral factors including:
  - Low fruit/vegetable consumption rates
  - No leisure-time physical activity rates
  - Other dietary and exercise behavioral indicators

### Statistical Analysis
- **Model Training**: Train-test split for validation
- **Feature Engineering**: Data preprocessing, filtering, and pivoting
- **Evaluation Metrics**:
  - **R² Score**: Proportion of variance explained (target: 0.4–0.6)
  - **RMSE**: Root Mean Square Error for prediction accuracy

## 📊 Dataset Details

**Source**: CDC's Nutrition, Physical Activity, and Obesity Dataset
- **Origin**: Behavioral Risk Factor Surveillance System (BRFSS)
- **Download**: [Kaggle CDC Dataset](https://www.kaggle.com/datasets/spittman1248/cdc-data-nutrition-physical-activity-obesity)
- **Scope**: Population-level aggregated survey data
- **Variables**: State, year, demographics, behavioral indicators, obesity rates
- **Format**: CSV format with behavioral health indicators

## 💻 Notebook/Code Features

### 🚀 Interactive Analysis Capabilities
- **Data Preprocessing**: Comprehensive data cleaning and transformation
- **Exploratory Data Analysis**: Statistical summaries and correlation analysis
- **Model Implementation**: Linear regression with scikit-learn
- **Performance Evaluation**: R² and RMSE metrics calculation
- **Visualization**: 
  - Scatter plots of actual vs. predicted values
  - Trend analysis graphs
  - Model performance visualizations

### 🔧 Code Structure
- Data loading and preprocessing functions
- Feature engineering and selection
- Model training and evaluation pipeline
- Visualization and results interpretation

## 📋 Requirements

### Dependencies
```python
# Core Libraries
pandas >= 1.3.0
numpy >= 1.21.0
scikit-learn >= 1.0.0
matplotlib >= 3.4.0

# Environment
Python 3.8+
```

### Installation
```bash
pip install pandas numpy scikit-learn matplotlib
```

## ☁️ Google Colab Integration Highlights

### 🌟 Interactive Colab Features
- **📁 Easy File Upload**: Built-in file upload functionality for dataset loading
- **🔄 One-Click Execution**: Run entire analysis with sequential cell execution
- **📈 Live Visualizations**: Interactive plots and charts rendered inline
- **💾 Cloud Storage**: Results and models saved to Google Drive integration
- **🔗 Shareable Analysis**: Easy sharing with collaborators and stakeholders

### 🚀 Colab Advantages
- **Zero Setup**: No local environment configuration required
- **GPU/TPU Support**: Enhanced computational capabilities if needed
- **Real-time Collaboration**: Multiple users can work simultaneously
- **Automatic Saving**: Progress saved automatically to Google Drive

### 📱 Access Methods
1. **Direct Upload**: Use the built-in file upload widget in the notebook
2. **Google Drive Mount**: Connect to your Drive for persistent storage
3. **Kaggle Integration**: Direct dataset download from Kaggle API

## 🎯 Getting Started

### Quick Start
1. **Clone Repository**: `git clone https://github.com/Yashas7206988696/ObesityTrend-LinearRegression.git`
2. **Install Dependencies**: `pip install -r requirements.txt`
3. **Download Dataset**: From Kaggle CDC dataset link above
4. **Run Analysis**: Execute the CODE file or open in Google Colab

### 🔬 Expected Results
- **Model Performance**: R² score typically ranges 0.4-0.6
- **Prediction Accuracy**: RMSE around 5-10% for obesity rate predictions
- **Insights**: Clear correlations between lifestyle factors and obesity trends

## 📈 Model Performance

- **R² Score**: Measures how well the model explains variance in obesity rates
- **RMSE**: Average prediction error in percentage points
- **Interpretability**: Linear coefficients show direct impact of each behavioral factor

## 🤝 Contributing

Contributions are welcome! Please feel free to submit pull requests or open issues for improvements.

## 📄 License

This project is available under the MIT License.

---

**Note**: This model provides population-level insights and should not be used for individual health predictions. For personal health assessments, consult healthcare professionals.
