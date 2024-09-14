
# Medical Insurance Pricing Analysis Project

## Project Overview

This project focuses on analyzing the factors that influence medical insurance pricing. The key objective is to examine relationships between several demographic and lifestyle factors such as BMI, age, smoking status, region, and medical charges. Additionally, the project implements machine learning models to predict insurance charges using these attributes.

### Key Steps of the Project
1. **Data Preprocessing**:
   - Normalization of continuous variables (e.g., Age, BMI, Medical Charges).
   - Encoding categorical variables (e.g., Sex, Smoker, Region) using one-hot encoding.
   - Log transformation of skewed features (e.g., Medical Charges) to ensure normal distribution.
   
2. **Exploratory Data Analysis**:
   - Visualizing raw distributions of key variables.
   - Performing correlation analysis to identify relationships between features.
   - Using statistical tests like Kolmogorov-Smirnov, Mann-Whitney U, and ANOVA to test hypotheses.

3. **Feature Engineering**:
   - Outlier removal using standard deviation thresholds.
   - Standardization and PCA for dimensionality reduction.
   - Feature selection based on importance measures.

4. **Machine Learning Models**:
   - Linear Regression, Random Forest, Support Vector Machines, and XGBoost models were trained and evaluated.
   - SHAP (SHapley Additive exPlanations) was used to interpret the models and identify the most important features for predicting medical charges.

### Dataset

The dataset used in this project is publicly available on [Kaggle](https://www.kaggle.com/datasets/mirichoi0218/insurance) and contains information about demographic and health-related attributes for 1,400 individuals, including:
- Age
- Sex
- BMI (Body Mass Index)
- Number of children
- Smoking status
- Region
- Medical charges

### How to Run

Follow these steps to set up and run the project:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Haimzis/KaggleMedicalInsurancePrediction.git
   ```

2. **Navigate to the project directory**:
   ```bash
   cd KaggleMedicalInsurancePrediction
   ```

3. **Install the required Python packages**:
   Make sure you have Python 3.x installed on your system. Run the following command to install all the required packages:
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Jupyter notebook**:
   After installing the dependencies, you can run the Jupyter notebook to reproduce the analysis:
   ```bash
   jupyter notebook
   ```

   Open the `notebook.ipynb` and run all the cells to perform the analysis and generate results.
