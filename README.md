# Diabetic Status Prediction Project

This project predicts the diabetic status of patients based on their health information using machine learning techniques.

## Overview

The goal is to develop a model that accurately classifies whether a patient is diabetic or not based on diagnostic measurements.

### Key Steps

1. **Data Collection and Analysis:**
   - Utilized the PIMA Diabetes Dataset.
   - Explored dataset statistics and class distributions.

2. **Data Preprocessing:**
   - Handled missing values.
   - Standardized features using `StandardScaler`.

3. **Model Training:**
   - Split data into training and testing sets.
   - Trained a Support Vector Machine (SVM) classifier with linear kernel.

4. **Model Evaluation:**
   - Assessed model performance using accuracy score on training and test sets.

5. **Making Predictions:**
   - Implemented a predictive system to classify new data inputs.

## Tools and Libraries Used

- Python
- Pandas
- NumPy
- Scikit-learn (sklearn)

## Files

- `diabetes.csv`: Dataset containing patient information.
- `diabetes_prediction.ipynb`: Jupyter notebook with project code.

## Usage

1. Clone this repository:
    git clone https://github.com/your_username/diabetic-status-prediction.git
2. Install dependencies:
3. Open and run `diabetes_prediction.ipynb` in Jupyter Notebook to see the code and results.
4. Modify `input_data` in the notebook to predict diabetic status for new inputs.

## Future Improvements

- Explore other machine learning algorithms.
- Optimize SVM hyperparameters.
- Enhance feature engineering for better predictions.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

