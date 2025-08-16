🧠 Glaucoma Detection Using CNN & Ensemble Learning
📌 Overview

This project focuses on the automated detection of Glaucoma from retinal fundus images. Glaucoma is one of the leading causes of blindness worldwide, and early detection is crucial.
We developed a hybrid deep learning approach that combines Convolutional Neural Networks (CNNs) with traditional machine learning classifiers to improve accuracy and robustness.

🚀 Features

Retinal image preprocessing for noise reduction and normalization and feature extraction using VGG16 CNN model (transfer learning)

Classification using:
Logistic Regression (LR),Decision Tree (DT),Random Forest (RF), Ensemble learning with Voting Classifier to combine model strengths,Evaluation using Accuracy, Precision, Recall, F1-score, Confusion Matrix, and ROC-AUC


📊 Results

Accuracy: ~91%, Precision: High (few false positives), Recall: High (important for medical diagnosis),F1-Score: Balanced performance,Confusion Matrix: Low false negatives

🛠️ Technologies Used

Python 3.10+, TensorFlow / Keras (for CNN - VGG16), Scikit-learn (for LR, DT, RF, Ensemble), Matplotlib & Seaborn (for visualization), NumPy & Pandas (for data handling)
