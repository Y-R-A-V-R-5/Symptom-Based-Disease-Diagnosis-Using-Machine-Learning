# Symptom-Based Disease Diagnosis Using Machine Learning

## Project Overview

This project aims to predict diseases based on symptoms using machine learning algorithms, enhancing early disease detection for improved healthcare outcomes. With the ever-increasing volume of medical data, it has become crucial to find efficient ways to analyze and make sense of this data. Machine learning plays a vital role in this by identifying hidden patterns in the data that may not be immediately obvious.

We utilize two powerful machine learning algorithms – **Random Forest** and **Support Vector Machine (SVM)** – to train models on symptom-disease datasets. These models can then be used to predict diseases from the symptoms provided by patients.

By leveraging these algorithms, we aim to improve the accuracy and speed of disease prediction, contributing to better early intervention and patient care.

## Features

- **Disease Prediction**: Predict diseases based on input symptoms, utilizing advanced machine learning techniques.
- **Random Forest Algorithm**: Used to create decision trees to classify diseases based on symptoms.
- **Support Vector Machine**: Used for classification, identifying the best hyperplane to separate different disease categories.
- **Data Preprocessing**: Cleans and prepares the dataset for use with machine learning models.
- **Early Diagnosis**: Aims to provide early disease detection to facilitate timely treatment.
- **Easy-to-use**: The tool is designed to be user-friendly, with a simple input method for symptoms and easy-to-understand predictions.

## Technologies & Tools Used

- **Programming Language**: Python
- **Machine Learning Libraries**:
  - **Scikit-learn**: For implementing machine learning algorithms (Random Forest, SVM).
  - **Pandas**: For data manipulation and analysis.
  - **NumPy**: For numerical operations.
- **Data Handling**: The project makes use of a dataset containing symptoms and their associated diseases.
- **IDE**: Python IDE (such as Jupyter Notebook, VS Code, or PyCharm) for development and testing.

## Team Members

This project was developed by a team of dedicated Computer Science students under the guidance of our professor. The team is composed of:

- **G. Shiva Sanjana** 
  - Lead Developer and Data Scientist
  - Responsible for implementing the core machine learning algorithms and training models.

- **P. Jaya Prakash Rao**
  - Backend Developer and Model Evaluator
  - Focused on developing the backend architecture for the prediction system and evaluating the performance of the machine learning models.
 
- **Y. Adithya Vardhan Reddy**
  - Data Analyst and Preprocessing Expert
  - In charge of data cleaning, preprocessing, and feature engineering to ensure the dataset is ready for machine learning.

## Professor

This project was completed under the esteemed guidance of:

- **Mrs. B. Vasavi Sravanthi**
  - Assistant Professor, Department of Computer Science and Engineering (CSE)
  - Her mentorship was crucial in guiding the team through the project's planning, development, and implementation phases.

## How It Works

1. **Dataset**: The dataset contains a collection of symptoms and corresponding diseases. This data is essential for training the machine learning models.
2. **Data Preprocessing**: The raw data is cleaned, and features are extracted to prepare the dataset for model training. This step includes handling missing values, encoding categorical variables, and normalizing data.
3. **Model Training**: We use two machine learning models to classify diseases:
   - **Random Forest**: An ensemble learning method that creates multiple decision trees and combines their results to produce a more accurate classification.
   - **Support Vector Machine (SVM)**: A powerful classification algorithm that separates classes using a hyperplane.
4. **Disease Prediction**: The trained models predict the disease based on input symptoms from the user. The system provides an output based on the model’s prediction.

## How to Run the Project

To run this project on your local machine, follow these steps:

### 1. Clone the Repository
First, clone the repository to your local machine:

```bash
git clone https://github.com/yourusername/symptom-disease-diagnosis.git
cd symptom-disease-diagnosis
