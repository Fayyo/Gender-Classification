# Gender-Classification
## Overview
This project focuses on building a gender classification model using machine learning techniques. The primary goal is to predict gender based on a given dataset of features. The best performance was achieved using a Logistic Regression model, which demonstrated high accuracy and interpretability.

## Project Structure
The project is divided into the following sections:

Data Preprocessing: Cleaning and preparing the dataset for analysis.
- Exploratory Data Analysis (EDA): Understanding the distribution of data and identifying key patterns.
- Model Selection: Training multiple machine learning models.
- Model Evaluation: Comparing the performance of different models.
- Best Model: Selecting Logistic Regression as the final model.
- Conclusion: Summarizing the findings and future directions.

## Dataset
The dataset used in this project contains approximately 5,000 rows with several features that describe facial attributes. Below is a summary of the dataset:

Columns: 8 key features
- long_hair: Binary attribute indicating if the individual has long hair.
- forehead_width_cm: The width of the forehead in centimeters.
- forehead_height_cm: The height of the forehead in centimeters.
- nose_wide: Binary attribute indicating if the nose is wide.
- nose_long: Binary attribute indicating if the nose is long.
- lips_thin: Binary attribute indicating if the lips are thin.
- distance_nose_to_lip_long: Binary attribute indicating if the distance from the nose to the lip is long.
- gender: Target variable, indicating the gender (male or female).

## Getting Started
To run this project locally, follow these steps:

1. Clone the repository:
git clone https://github.com/Fayyo/Gender-Classification.git

2. Install dependencies: Make sure you have Python installed. Then, install the required libraries:
pip install -r requirements.txt

3. Run the Jupyter Notebook: Launch the notebook to view and execute the code:
jupyter notebook Gender_Classification.ipynb

## Dependencies
Below are the primary libraries used in this project:
- Pandas: For data manipulation and analysis.
- NumPy: For numerical computations.
- Matplotlib & Seaborn: For data visualization.
- Scikit-Learn: For implementing and evaluating machine learning models.

## Exploratory Data Analysis
The dataset was explored to identify patterns and relationships between features. Key visualizations were created to understand the feature distributions and correlations. This step helped in identifying the most relevant features for the classification task.

## Model Training and Evaluation
Several machine learning models were trained, including:
- Logistic Regression (Final model)
- Decision Tree
- Random Forest
The Logistic Regression model was selected due to its high accuracy and interpretability.
Performance metrics like accuracy, precision, recall, and F1-score were used to evaluate the models.

## Results
The Logistic Regression model achieved the best performance with the following metrics:

- Accuracy: 0.97
- Precision: 0.97
- Recall: 0.98
- F1-Score: 0.97

## Conclusion
The project successfully demonstrated the use of Logistic Regression for gender classification. The model showed a strong ability to distinguish between genders based on the given features. Future work may involve incorporating additional features or exploring more complex models to improve classification accuracy.
