# Gamma-Particle-Classification-using-Machine-Learning
Built a machine learning project using the Magic Telescope dataset to classify gamma and hadron particles. Performed preprocessing, scaling, and handled class imbalance using oversampling. Trained KNN, Naive Bayes, Logistic Regression, SVM, and a TensorFlow neural network with hyperparameter tuning and performance evaluation.

# More Detailed Explanation :
his project focuses on solving a binary classification problem using the Magic Telescope dataset.

The workflow starts with data loading and preprocessing, including converting categorical labels into numerical format and analyzing feature distributions. The dataset is split into training, validation, and testing sets.

To address class imbalance, RandomOverSampler is applied to the training data. Feature scaling is performed using StandardScaler to normalize the input features.

Multiple classical machine learning models are implemented and evaluated, including K Nearest Neighbors with different configurations, Naive Bayes, Logistic Regression, and Support Vector Machine. Their performance is compared using classification metrics.

In addition to classical models, a neural network is built using TensorFlow. Different hyperparameters such as number of nodes, dropout rate, learning rate, and batch size are tested to find the best configuration. Model performance is analyzed using accuracy and loss curves.

This project demonstrates a complete machine learning pipeline from data preprocessing to model evaluation and comparison.

#Dataset Credits :
https://archive.ics.uci.edu/dataset/159/magic+gamma+telescope
