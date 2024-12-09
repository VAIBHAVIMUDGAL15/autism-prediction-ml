
# Autism Prediction Using Machine Learning

This project leverages machine learning to predict autism spectrum disorders (ASD) using a structured dataset. By applying data preprocessing, exploratory analysis, and various machine learning models, the project provides insights into key factors influencing autism diagnosis.

## Features

- **Data Preprocessing**: Handled missing values, encoded categorical features, and normalized data for improved model performance.
- **Exploratory Data Analysis (EDA)**: Visualized patterns and correlations to identify significant predictors of autism.
- **Model Development**: Implemented machine learning algorithms (e.g., Logistic Regression, Decision Trees, Random Forest) to predict autism likelihood.
- **Evaluation**: Assessed model performance using metrics like accuracy, precision, recall, and F1-score.

## Dataset

The project uses the provided dataset (`train.csv`), which includes demographic, diagnostic, and behavioral traits related to autism.

## Key Steps

1. Load and preprocess the dataset.
2. Perform EDA to explore feature distributions and relationships.
3. Train machine learning models and optimize them for better accuracy.
4. Evaluate model performance and visualize feature importance.

## Libraries Used

- **Data Manipulation**: numpy, pandas
- **Visualization**: matplotlib, seaborn
- **Machine Learning**: scikit-learn
- **Utilities**: pickle for saving the model

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/VAIBHAVIMUDGAL15/autism-prediction-ml.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook Autism_Preidiction_using_machine_Learning.ipynb
   ```

## Results

The trained models demonstrated high accuracy in predicting autism, highlighting the importance of specific features in diagnosis. Visualization of feature importance provided additional insights into key factors influencing predictions.
