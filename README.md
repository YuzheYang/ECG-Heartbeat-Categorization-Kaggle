# ECG-Heartbeat-Categorization-Kaggle
This is a public repository for Kaggle competition ECG Heartbeat Categorization.
The source of data is available on https://www.kaggle.com/shayanfazeli/heartbeat

This dataset is composed of two collections of heartbeat signals derived from two famous datasets in heartbeat classification, the MIT-BIH Arrhythmia Dataset and The PTB Diagnostic ECG Database. This repository is designed for a classification task based on ECG signal. The signals correspond to electrocardiogram (ECG) shapes of heartbeats for the normal case and the cases affected by different arrhythmias and myocardial infarction. These signals are preprocessed and segmented, with each segment corresponding to a heartbeat. In this repository, we designed a simple convolutional neural network to classify the pattern of heartbeats.

The results indicate that the accuracy of our model can reach around 0.985 on test data after 20 Epochs.

Epoch 20/20
1369/1369 [==============================] - 10s 7ms/step - loss: 0.0213 - categorical_accuracy: 0.9928 - val_loss: 0.0831 - val_categorical_accuracy: 0.9848

# Acknowledge:
Mohammad Kachuee, Shayan Fazeli, and Majid Sarrafzadeh. "ECG Heartbeat Classification: A Deep Transferable Representation." arXiv preprint arXiv:1805.00794 (2018).
