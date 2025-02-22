Overview

This repository provides an implementation of supervised learning techniques for detecting electricity theft. The project explores different machine learning models, including Decision Trees (DT), Artificial Neural Networks (ANN), Deep Artificial Neural Networks (DANN), and AdaBoost, to classify electricity consumption patterns and identify potential theft cases.

Dataset

The study is based on an electricity consumption dataset, which consists of:

Features representing electricity usage patterns.

Labels indicating normal consumption (0) or suspected electricity theft (1).

Note: The dataset used in this implementation is simulated for demonstration purposes. Replace it with real-world data for actual results.

Models Implemented

Decision Tree (DT): A simple yet effective model for classification tasks.

AdaBoost: An ensemble learning technique that improves weak classifiers.

Artificial Neural Network (ANN): A neural network with one hidden layer for better feature representation.

Deep Artificial Neural Network (DANN): A multi-layer neural network for improved classification performance.

Evaluation Metrics

The models are evaluated based on:

Accuracy: Measures overall correctness.

Precision: Measures correctness of theft predictions.

Recall: Measures ability to detect theft cases.

F1-Score: Harmonic mean of Precision and Recall.

AUC (Area Under ROC Curve): Measures model separability.

Results

The results show that deep learning models (ANN, DANN) generally perform better in detecting electricity theft compared to traditional classifiers like Decision Tree and AdaBoost. However, the best model selection depends on dataset characteristics and computational constraints.

Future Improvements

Experiment with other supervised learning models (e.g., Random Forest, SVM, XGBoost).

Optimize hyperparameters for better performance.

Implement anomaly detection techniques for unsupervised learning.

Contributors

Your Name

License

This project is licensed under the MIT License - see the LICENSE file for details.

References

Original research article: "A Comprehensive Analysis of Supervised Learning Techniques for Electricity Theft Detection."

Machine learning documentation: Scikit-learn, TensorFlow

