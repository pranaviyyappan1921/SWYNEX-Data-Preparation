# Task 3: Baseline Machine Learning Model

## Objective
Build and evaluate a baseline machine-learning model using the Adult Income Dataset to predict income categories.

## Dataset
- **Name:** Adult Income Dataset
- **Target Variable:** `income`
- **Classes:** `<=50K` and `>50K`

## Tools and Technologies
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Google Colab

## Tasks Performed
1. Loaded the cleaned Adult Income Dataset.
2. Separated input features and the target variable.
3. Split the dataset into training and testing sets using an 80:20 ratio.
4. Preprocessed numerical and categorical features.
5. Built and trained a Logistic Regression classifier.
6. Evaluated the model using accuracy, precision, recall, and F1-score.
7. Visualized model predictions using a confusion matrix.
8. Documented the limitations of the baseline model.

## Model Evaluation
The model was evaluated using the following metrics:
- **Accuracy:** Overall proportion of correct predictions.
- **Precision:** Proportion of positive predictions that are correct.
- **Recall:** Proportion of actual positive cases correctly identified.
- **F1-score:** Harmonic mean of precision and recall.
- **Confusion Matrix:** Shows correct and incorrect predictions for each income category.

Refer to the notebook for the actual evaluation results.

## Limitations
- The dataset has an imbalance between income categories.
- Historical data may contain demographic biases.
- Logistic Regression may not capture complex nonlinear relationships.
- The dataset may not represent all populations or current income conditions.
- Accuracy alone is not sufficient to assess model performance.

## Conclusion
A baseline Logistic Regression model was developed to predict income categories. Evaluation metrics and a confusion matrix were used to assess its performance. This baseline provides a starting point for future experiments with other machine-learning algorithms.

## Project Files
- `SWYNEX_Task3_Baseline_Model.ipynb` — notebook containing the model implementation, evaluation, and findings.
- `README.md` — project documentation.