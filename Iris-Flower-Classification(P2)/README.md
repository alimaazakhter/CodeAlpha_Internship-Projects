***Model Evaluation Summary:***

✅ Accuracy Score:
1.0 (💯 means 100% correct predictions on test data — amazing!)

✅ Classification Report:

| Class (Species)  | Precision | Recall | F1-Score | Support |
| ---------------- | --------- | ------ | -------- | ------- |
| Setosa (`0`)     | 1.00      | 1.00   | 1.00     | 10      |
| Versicolor (`1`) | 1.00      | 1.00   | 1.00     | 9       |
| Virginica (`2`)  | 1.00      | 1.00   | 1.00     | 11      |

🧠 Terms Meaning:

1. Precision: Model predicted the correct class without being wrong.
2. Recall: Model caught all the actual examples of that class.
3. F1-Score: Combined score (precision + recall), so 1.00 means perfect balance.
4. Support: Actual number of samples per class in test data.

✅ Confusion Matrix:
It showed 0 misclassifications, meaning each sample was correctly predicted into its actual class.

📌 Conclusion:
The model performs perfectly on the test data. It has learned how to distinguish Setosa, Versicolor, and Virginica with full confidence. 
✅ This is expected because Iris is a very clean and well-behaved dataset.

