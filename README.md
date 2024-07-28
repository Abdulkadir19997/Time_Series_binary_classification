
# Time Series Binary Classification

This repository contains a Jupyter notebook that demonstrates a time series binary classification task using various machine learning techniques. The primary focus is on using the Random Forest algorithm to achieve high classification accuracy.

## Overview

In this notebook, we address the challenge of classifying time series data into binary categories. The notebook includes the following key steps:

1. **Data Loading and Preprocessing:**
   - Importing necessary libraries.
   - Loading and examining the dataset.
   - Preprocessing the data, including handling missing values and feature scaling.

2. **Exploratory Data Analysis (EDA):**
   - Visualizing the data to understand the underlying patterns.
   - Plotting time series trends and distributions of the features.

3. **Feature Engineering:**
   - Creating relevant features from the time series data.
   - Ensuring the data is ready for machine learning models.

4. **Model Training and Evaluation:**
   - Splitting the data into training and testing sets.
   - Training a Random Forest classifier.
   - Evaluating the model using accuracy, precision, recall, and F1-score metrics.
   - Visualizing the ROC curve and calculating the AUC score.

5. **Conclusion:**
   - Summary of the obtained results.
   - Discussion on potential overfitting and future steps.

## Technologies Used

- **Python 3.9:** The primary programming language used for data analysis and model building.
- **Jupyter Notebook:** An interactive environment for executing Python code and visualizing results.
- **Pandas:** A powerful data manipulation library.
- **NumPy:** A fundamental package for scientific computing.
- **Matplotlib & Seaborn:** Libraries for creating static, animated, and interactive visualizations.
- **Scikit-learn:** A machine learning library for model training and evaluation.

## How to Use

1. **Clone the Repository:**

   ```sh
   git clone https://github.com/Abdulkadir19997/Time_Series_binary_classification.git
   cd Time-Series-Binary-Classification
   ```

2. **Install Dependencies:**

   Ensure you have Python 3.9 installed. Then, install the required packages:

   ```sh
   pip install -r requirements.txt
   ```

3. **Run the Notebook:**

   Open the Jupyter notebook:

   ```sh
   jupyter notebook Time_series_binary_classification.ipynb
   ```

   Execute the cells in the notebook to see the data analysis and model training steps.

## Results

The Random Forest classifier achieved the following results:

- **Accuracy:** 100%
- **Precision:** 100% for both classes
- **Recall:** 100% for both classes
- **F1-score:** 100% for both classes

These results indicate potential overfitting, suggesting the need for more data and further validation.

## Future Work

To ensure the model's robustness and applicability in real-world scenarios, the following steps are recommended:

- Collecting more data to train and validate the model.
- Testing the model with real-time data from the application domain.
- Exploring other classification algorithms and hyperparameter tuning to improve generalization.

