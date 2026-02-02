Sampling Assignment – Credit Card Fraud Detection



📌 Objective

The objective of this assignment is to study the impact of different sampling techniques on highly imbalanced datasets and analyze how these techniques affect the performance of multiple machine learning models.



📊 Dataset

The dataset used is a credit card fraud detection dataset, which is highly imbalanced.

\- Source: https://github.com/AnjulaMehto/Sampling\_Assignment/blob/main/Creditcard\_data.csv

\- Target variable: `Class` (0 = Non-fraud, 1 = Fraud)



⚙️ Sampling Techniques Used

1\. Random Oversampling

2\. SMOTE (Synthetic Minority Oversampling Technique)

3\. ADASYN

4\. Random Undersampling

5\. SMOTEENN (Hybrid Sampling)



🤖 Machine Learning Models Used

1\. Logistic Regression

2\. Decision Tree

3\. Random Forest

4\. Support Vector Machine (SVM)

5\. K-Nearest Neighbors (KNN)



🧪 Methodology

\- The dataset was first scaled using `StandardScaler`.

\- It was then balanced using different sampling techniques.

\- Each sampling technique was applied to the training data.

\- Each model was trained and evaluated using accuracy.

\- A comparison table and heatmap were generated.


📈 Results

A results table was generated showing the accuracy (%) of each model under each sampling technique. The best sampling method for each model was identified.


🏆 Observations

\- Some models performed better with oversampling techniques like SMOTE and ADASYN.

\- Ensemble models like Random Forest showed stable performance across techniques.

\- Undersampling generally resulted in lower accuracy due to loss of majority class data.



✅ Conclusion

Sampling techniques significantly impact model performance on imbalanced datasets. Choosing the right technique depends on the model and the nature of the data.




