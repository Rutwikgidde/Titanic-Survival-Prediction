# Titanic Survival Prediction

## Project Overview

This project aims to develop a machine learning model to predict whether a passenger survived the Titanic disaster. The dataset includes features like age, gender, ticket class, fare, and cabin information. The model is trained using classification techniques with proper data preprocessing and evaluation.

## Dataset

The dataset used in this project contains information about Titanic passengers, including:

- **Features:** Age, Gender, Ticket Class (Pclass), Fare, Cabin, and more.
- **Target Variable:** Survived (1 for survived, 0 for not survived).

## Preprocessing Steps

1. **Handling Missing Values**
   - Imputation of missing values in Age, Fare, and Cabin columns.
2. **Encoding Categorical Variables**
   - Converted 'Sex' column into numerical format (0: Male, 1: Female).
   - One-hot encoding for 'Pclass' (Ticket Class).
3. **Feature Scaling**
   - Standardization applied to numerical features (Age, Fare) for better model performance.

## Model Selection & Training

- **Algorithm Used:** Random Forest Classifier
- **Training Process:**
  1. Splitting data into training and testing sets (80:20 ratio).
  2. Training the model on training data.
  3. Evaluating performance using accuracy, precision, and other metrics.

## Performance Analysis

- **Accuracy:** Measures overall correctness of the model.
- **Precision:** Evaluates the positive class predictions to minimize false positives.
- The model is evaluated to ensure it generalizes well to unseen data.

## How to Run the Notebook

1. Clone the repository:
   ```bash
   git clone <repository-link>
   ```
2. Navigate to the directory:
   ```bash
   cd <repository-folder>
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Open and run the Jupyter Notebook:
   ```bash
   jupyter notebook project_updated.ipynb
   ```

## Conclusion

This project successfully implements a machine learning model to predict Titanic survival with proper preprocessing, feature engineering, and performance evaluation. The notebook follows a structured workflow, making it easy to understand and modify.

---

For any questions or contributions, feel free to open an issue or submit a pull request in the repository!

