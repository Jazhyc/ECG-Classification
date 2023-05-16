# ECG-Classification

The human heart is a biological marvel where failure to function properly for even a moment can lead to catastrophic consequences. Therefore, there is a great incentive to detect and diagnose heart disease as early as possible. An electrocardiogram (ECG) is a test that measures the electrical signals of the heart. However, the interpretation of ECGs is a complex process which requires years of training for humans. [Khan et al. (2023)](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0284791) have developed a 1D Convolutional Neural Network (CNN) which can classify pathological ECGs with an average accuracy of 98.63% without fine-tuning the model on the data of each individual patient. This project serves as a replication of their work and we plan to compare the accuracy of our general model to one that is solely trained on the data of each individual patient.
