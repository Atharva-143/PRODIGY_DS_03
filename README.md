### Task-03: Decision Tree Classifier – Bank Marketing Dataset

Internship: Data Science Internship – Prodigy InfoTech

---

### Objective
To build a Decision Tree classifier that predicts whether a customer will purchase a product or service based on demographic and behavioral data.

---

### Dataset
Source: Bank Marketing Dataset (UCI Machine Learning Repository)

Description:  
The dataset contains information related to direct marketing campaigns of a banking institution. It includes customer demographics, contact information, and previous campaign outcomes. The target variable indicates whether the customer subscribed to a product (yes/no).

---

### Data Preprocessing
- Loaded the dataset using pandas.
- Identified the target variable (`y`).
- Converted categorical variables into numerical format using one-hot encoding.
- Encoded the target variable (`yes` → 1, `no` → 0).
- Split the dataset into training and testing sets using an 80:20 ratio.

---

### Model Building
- Built a Decision Tree Classifier using scikit-learn.
- Limited tree depth to prevent overfitting.
- Trained the model on the training dataset.

---

### Model Evaluation
- Evaluated the model using accuracy score.
- Generated a classification report to assess precision, recall, and F1-score.
- Visualized model performance using a confusion matrix.
- Visualized the trained Decision Tree for interpretability.

---

### Results
- The model achieved an accuracy of approximately 90%.
- The classifier performed well in predicting customers who did not subscribe.
- The decision tree visualization provides insight into the factors influencing customer decisions.

---

### Conclusion
This task demonstrates the application of a Decision Tree classifier to a real-world business dataset. The analysis highlights how demographic and behavioral factors can be used to predict customer purchasing decisions effectively.
