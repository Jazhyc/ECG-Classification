# ECG-Classification using ResNet

The human heart is a biological marvel where failure to function properly can lead to catastrophic consequences. Therefore, there is a great incentive for the rapid and accurate diagnosis of heart disease. An electrocardiogram (ECG) is a test that measures the electrical signals of the heart. However, interpreting ECGs is a complex process that requires years of professional training and experience. This project makes use of a one-dimensional residual convolutional neural network (ResNet) to classify individual heartbeats using the PhysioNet MIT-BIH Arrhythmia database. Our pre-processing pipeline makes use of the Pam-Tompkins algorithm to extract features and the SMOTE oversampling technique to over-sample the minority heartbeats. We make use of 5-fold cross-validation to determine the optimum regularization hyper-parameter and assess our model using accuracy, precision, sensitivity, and specificity. An analysis of our model with these metrics reveals that it is comparable with other ECG classification techniques. However, there is scope for improvement as our model still struggles to properly classify minority heartbeat classes in the database.

## Research Paper

[Link to Paper](Machine_Learning_Report.pdf)
