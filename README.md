# Project Introduction

The primary objective of this AI project is to develop a robust and accurate machine learning system capable of predicting whether a car driver will stop by a local store when exposed to promotional advertisements broadcasted on the car radio during their journey. This project seeks to harness the power of artificial intelligence to enhance the efficiency and effectiveness of targeted marketing strategies in the retail industry. By leveraging advanced data analytics and machine learning algorithms, our goal is to model and predict consumer behavior in response to radio promotions, providing valuable insights to businesses aiming to optimize their advertising campaigns.

# Project Conclusion

In our approach, we initially conducted training without using SMOTE and later applied SMOTE. The training phase involved five classifiers: Random Forest, Logistic Regression, Stochastic Gradient Descent (SGD), Extreme Gradient Boosting (XGBoost), and K-Nearest Neighbor (KNN). Each classifier underwent a 5-fold cross-validation to evaluate its performance, with a focus on precision-recall graphs, receiver operating characteristic (ROC) curves, and Area under the ROC Curve (AUC) scores for comparison.

Our conclusion highlighted XGBoost as the most effective algorithm, utilizing specific hyperparameters (gamma: 0, learning rate: 0.1, max depth: 5). XGBoost consistently exhibited the highest scores in accuracy, precision, recall, and f1 score, and it demonstrated lower variability between training and testing scores compared to other models.
