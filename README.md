# diabetes_prediction_file


# Diabetes Prediction Using Support Vector Machine (SVM)

This project aims to predict the likelihood of a patient having diabetes based on medical diagnostic measurements. The prediction model is built using a Support Vector Machine (SVM) classifier.

## Dataset

The dataset used for this project is the **Pima Indians Diabetes Database**, which contains the following attributes:

1. Pregnancies
2. Glucose
3. Blood Pressure
4. Skin Thickness
5. Insulin
6. BMI
7. Diabetes Pedigree Function
8. Age
9. Outcome (0 = Non-diabetic, 1 = Diabetic)

## Model Overview

The SVM classifier was chosen for its effectiveness in high-dimensional spaces and its ability to handle both linear and non-linear data. The model was trained on a portion of the dataset and tested on the remaining data to evaluate its performance.

### Results

The model achieved an accuracy of **77%** on the test set. While this is a solid result, further improvements can be made through techniques such as hyperparameter tuning, feature engineering, and handling class imbalances.

## How to Run

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/diabetes-prediction-svm.git
   cd diabetes-prediction-svm
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the model**:
   ```bash
   python svm_diabetes_prediction.py
   ```

## Future Work

- **Hyperparameter Tuning**: Experiment with different kernels, `C`, and `gamma` values.
- **Feature Engineering**: Create and select features that could improve model performance.
- **Handling Imbalanced Data**: Apply techniques like SMOTE or class weighting to address class imbalance.
- **Cross-Validation**: Implement k-fold cross-validation for more robust model evaluation.
- **Ensemble Methods**: Explore combining SVM with other machine learning models.

## Contributing

Contributions are welcome! Please fork this repository and submit a pull request with your improvements.

## License

This project is licensed under the MIT License.

---

Feel free to adjust any sections according to your project's specifics!
