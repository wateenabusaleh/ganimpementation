# ganimpementation
GANs for Fraud Detection
An implementation of Vanilla GAN, WGAN, and LSGAN using PyTorch.

This project addresses the "Class Imbalance" problem in financial data by generating synthetic fraud samples to improve classifier performance.

*Key Features:
Vanilla GAN: Baseline architecture for synthetic anomaly generation.

WGAN (Wasserstein GAN): Features weight clipping and RMSprop for training stability.

LSGAN (Least Squares GAN): Uses MSELoss to solve the vanishing gradient problem.

📊 Results:
Augmenting the training set improved the Recall and AUC-ROC scores on the Credit Card Fraud Detection dataset.

Run it on Google Colab
