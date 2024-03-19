# UW560

Breast cancer is the most common cancer amongst women in the world. It accounts for 25% of all cancer cases and affected over 2.1 Million people in 2015 alone. It starts when cells in the breast begin to grow out of control. These cells usually form tumors that can be seen via X-ray or felt as lumps in the breast area.

## SVM (Support Vector Machine) Metrics:
- **Accuracy:** 98.23%
- The SVM model is highly accurate with a 98.23% success rate in predicting the correct class (benign or malignant) for the given data. This indicates that the model is highly effective for this dataset.
- **Precision:** 100%
- The precision of 1 (or 100%) means that every instance predicted as malignant by the SVM model was indeed malignant. This indicates a very low false positive rate, which is particularly important in medical diagnostics.
- **Recall:** 97.18%
- The recall (or sensitivity) of 97.18% indicates that the model successfully identified 97.18% of all actual malignant cases. This is a strong performance, although there's a small margin where the model may miss malignant cases.

## KNN (k-Nearest Neighbors) Metrics:
- **Accuracy:** 91.15%
- The KNN model has an accuracy of 91.15%, which is high but not as high as the SVM model. This suggests that while effective, KNN may not capture all nuances in the data compared to SVM in this instance.
- **Precision:** 94.20%
- The precision of 94.20% is excellent, indicating that most of the malignant predictions by KNN are correct, but it is slightly lower than SVM's precision.
- **Recall:** 91.55%
- The recall rate is also high at 91.55%, indicating the model is reliable in identifying malignant cases, but again, it falls short of the SVM's recall rate.

## Logistic Regression Metrics:
- **Accuracy:** 93.81%
- The logistic regression model offers a high accuracy rate of 93.81%, situating it between the SVM and KNN models in terms of overall performance.
- **Precision:** 100%
- Like SVM, logistic regression shows a precision of 100%, meaning there are no false positives among the predicted malignant cases, which is an ideal scenario for precision-focused domains.
- **Recall:** 90.14%
- The recall is lower than both SVM and KNN models, indicating that while logistic regression is very confident in its predictions (as shown by its precision), it misses more actual malignant cases compared to the other models.

## Summary:
- The SVM model exhibits the best overall performance among the three models in terms of accuracy and balance between precision and recall. It is the most reliable model for classifying the conditions as either benign or malignant with minimal errors.
- The KNN model shows good performance but is slightly less accurate and precise than the SVM model. Its recall is also slightly less than the SVM, making it a second choice if the SVM model is not available.
- The Logistic Regression model demonstrates high precision but lags slightly behind in recall, indicating it may not identify all malignant cases, even though it doesn't falsely label benign cases as malignant.

Each model has its strengths and could be chosen based on the specific requirements of a healthcare scenario: SVM for overall best performance, KNN for a slightly more balanced approach if computational resources are limited, and Logistic Regression when false positives must be minimized at all costs.
