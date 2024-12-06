# Diabetes Prediction

This project aims to predict whether a person has diabetes or not using various machine learning techniques. The dataset used contains several medical predictor variables and one target variable, Outcome.

## Project Overview

The project follows these main steps:
1. **Data Collection and Analysis**:
    - Load the dataset.
    - Perform exploratory data analysis.
2. **Data Preprocessing**:
    - Handle missing values.
    - Standardize the features.
3. **Model Training**:
    - Split the data into training and testing sets.
    - Train a Support Vector Machine (SVM) model.
4. **Model Evaluation**:
    - Evaluate the model's performance using accuracy metrics.
    - Validate the model with a prediction system.

## Dependencies

The project requires the following dependencies:
- Python 3.x
- Pandas
- NumPy
- Scikit-learn

## Installation

1. Clone this repository:
    ```sh
    git clone https://github.com/DarkLord-13/Machine-Learning-01.git
    ```

2. Navigate to the project directory:
    ```sh
    cd Machine-Learning-01
    ```

3. Install the required packages:
    ```sh
    pip install pandas numpy scikit-learn
    ```

4. Open the Jupyter Notebook `DiabetesPrediction.ipynb` and run the cells to execute the project steps:
    ```sh
    jupyter notebook DiabetesPrediction.ipynb
    ```

## Usage

1. **Data Collection and Analysis**:
    - Load the dataset using Pandas.
    - Perform exploratory data analysis to understand the data distribution.

2. **Data Preprocessing**:
    - Handle missing values if any.
    - Standardize the features to bring them to a similar scale.

3. **Model Training**:
    - Split the data into training and testing sets using `train_test_split`.
    - Train a Support Vector Machine (SVM) model on the standardized features.

4. **Model Evaluation**:
    - Evaluate the model's performance using accuracy metrics.
    - Validate the model with a sample input to predict the outcome.

## Results

The trained SVM model will predict whether a person has diabetes based on their medical attributes. The performance of the model can be evaluated using training and testing accuracy.

## License

This project is licensed under the MIT License.
