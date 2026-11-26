# Loan_Approval_Prediction
Machine Learning project to predict loan approval using classification algorithms.
## Model Performance and Results

Three Machine Learning classification algorithms were implemented and evaluated.

### Accuracy Comparison

| Algorithm | Accuracy |
|---|---:|
| Logistic Regression | 86.18% |
| Decision Tree | 82.11% |
| Random Forest | 85.37% |

### Classification Report

**1. Logistic Regression**

- Precision: 0.90 (macro average)
- Recall: 0.78 (macro average)
- F1-score: 0.81 (macro average)
- Accuracy: 86.18%

**2. Decision Tree**

- Precision: 0.82 (macro average)
- Recall: 0.75 (macro average)
- F1-score: 0.77 (macro average)
- Accuracy: 82.11%

**3. Random Forest**

- Precision: 0.89 (macro average)
- Recall: 0.77 (macro average)
- F1-score: 0.80 (macro average)
- Accuracy: 85.37%

### Best Performing Model

Logistic Regression achieved the highest accuracy of 86.18%. However, its recall for the rejected-loan class was 58%, highlighting the need for further model evaluation.

It was selected as the best-performing model based on accuracy. However, its recall for the rejected-loan class was only 0.58, indicating that the model missed a substantial number of actual rejected cases.

Therefore, accuracy alone is not sufficient to evaluate this model.

## Project Conclusion

This project demonstrates the application of Machine Learning classification algorithms to loan approval prediction.

The workflow included data cleaning, exploratory data analysis, missing-value handling, feature encoding, feature scaling, model training, and evaluation.

Among the three algorithms, Logistic Regression achieved the highest accuracy of 86.18% on the test dataset.

The project provided practical experience in implementing an end-to-end Machine Learning workflow using Python and Scikit-learn.

## Limitations

- The dataset contains a limited number of historical loan applications.
- Missing values may affect model performance.
- Historical loan decisions may contain biases.
- The model has relatively low recall for the rejected-loan class.
- Accuracy alone cannot establish model fairness or reliability.
- The model is intended for educational purposes and not actual lending decisions.

## Future Enhancements

- Hyperparameter tuning to improve model performance.
- Fairness evaluation across applicant groups.
- Testing additional classification algorithms.
- Developing an interactive web application using Streamlit.
- Evaluating models using additional performance metrics.
