# Model Comparison Report
In this project, multiple machine learning models were developed and evaluated to classify whether a person is walking or
 running based on motion sensor data. The models were compared using various performance metrics such as accuracy, precision, 
 recall, F1-score, confusion matrix, and ROC-AUC curve to determine the most suitable model for deployment..

### Models Implemented

The following models were trained and tested:

* Logistic Regression
* Random Forest Classifier
* Artificial Neural Network (ANN)

### Evaluation Metrics Used
To ensure a fair and comprehensive comparison, the following metrics were used:
* Accuracy: Measures overall correctness of the model
* Precision: Measures how many predicted positives are actually correct
* Recall: Measures how many actual positives are correctly identified
* F1-Score: Harmonic mean of precision and recall
* Confusion Matrix: Shows classification errors
* ROC-AUC Curve: Measures model’s ability to distinguish between classes

### Final Model Selection
-> Selected Model: <B> "Random Forest"

Random Forest is selected as the best model for the following reasons:

* Provides high accuracy with consistent performance
* Handles non-linear relationships effectively
* Less prone to overfitting compared to ANN
* Requires minimal hyperparameter tuning
* Performs well on real-world noisy sensor data
* Easier to deploy compared to deep learning models


| Model               | Accuracy  | Stability | Overfitting Risk | Complexity | Suitability |
| ------------------- | --------- | --------- | ---------------- | ---------- | ----------- |
| Logistic Regression | Medium    | High      | Low              | Low        | Baseline    |
| Random Forest       | High      | High      | Low              | Medium     | Best        |
| ANN                 | Very High | Medium    | High             | High       | Advanced    |
