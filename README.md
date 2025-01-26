Performance Analysis of Machine Learning Models Using Sampling Techniques

M1: Random Forest Classifier
Top Sampling Method: Sampling2 (Accuracy: 1.00)
Explanation: The Random Forest performed best with Random Over-Sampling. This method likely helped the model by balancing the dataset and giving it better exposure to the minority class, leading to improved learning.

M2: Logistic Regression
Top Sampling Method: Sampling5 (Accuracy: 1.00)
Explanation: NearMiss sampling gave the best results for Logistic Regression. By selectively removing majority class samples, the method seems to have improved the model’s ability to classify correctly.

M3: Support Vector Classifier (SVC)
Top Sampling Method: Sampling5 (Accuracy: 1.00)
Explanation: SVC, like Logistic Regression, benefited most from NearMiss sampling. This approach likely reduced dataset noise, offering a better balance and improving classification accuracy.

M4: Decision Tree Classifier
Top Sampling Method: Sampling2 (Accuracy: 0.993)
Explanation: Random Over-Sampling worked best for the Decision Tree. With more balanced data, the model could make more accurate decisions, which contributed to its strong performance.

M5: K-Nearest Neighbors (KNN)
Top Sampling Method: Sampling5 (Accuracy: 1.00)
Explanation: NearMiss was the most effective for KNN. By reducing the dominance of the majority class, this method tackled the inherent challenges KNN faces with imbalanced datasets, leading to better results.

Key Takeaways
Random Over-Sampling (Sampling2): A clear winner for Random Forest and Decision Tree models, this method leveraged additional balanced data to improve their performance.

NearMiss (Sampling5): Proved to be the most effective for models like Logistic Regression, SVC, and KNN, showing the power of selective undersampling in handling imbalanced datasets.

SMOTE-based Methods (Sampling3 & Sampling4): While these techniques performed reasonably well, they did not surpass Random Over-Sampling or NearMiss in terms of accuracy.

This analysis underscores the importance of choosing the right sampling method tailored to the strengths and weaknesses of each machine learning model.
