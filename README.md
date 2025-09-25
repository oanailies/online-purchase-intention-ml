This project focuses on predicting the purchasing intention of online shoppers using the UCI "Online Shoppers Purchasing Intention" dataset. The dataset contains 12,330 sessions with both numerical and categorical features describing user behavior, such as administrative, informational, and product-related interactions, bounce rates, exit rates, page values, visitor type, and whether the session occurred during the weekend.

The workflow includes:

Data exploration and visualization (distributions, correlations, stacked bar plots, box plots, density plots)

Data preprocessing (handling categorical variables, feature scaling, train/test split)

Addressing class imbalance through appropriate techniques

Training and evaluating machine learning models such as K-Nearest Neighbors (KNN) and Artificial Neural Networks (ANN)

Model evaluation using confusion matrix, classification report, ROC-AUC, and precision-recall metrics

Clustering experiments with K-Means for customer segmentation

The ANN model is implemented with TensorFlow/Keras, consisting of two hidden layers (64 and 32 neurons with ReLU activation) and a sigmoid output layer for binary classification. The model achieves high accuracy on the test set, demonstrating the potential of deep learning techniques in predicting online purchasing behavior.
