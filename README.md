# Waste Classification using CNN — Week 1 Progress

In Week 1 of my Waste Classification using CNN project, I began by setting up the environment using Google Colab and Google Drive. The objective of this project is to build a Convolutional Neural Network (CNN) model that classifies waste into two categories — Organic (O) and Recyclable (R) — using the Kaggle dataset Waste Classification with CNN
 by Beyza Nur Nakkaş. I organized the dataset into DATASET/TRAIN and DATASET/TEST folders, each containing subfolders for both classes, and uploaded them into my Drive under Waste_Classification_Project. After mounting Google Drive in Colab, I verified the paths to ensure proper data access and structure.

Next, I performed dataset preprocessing using TensorFlow’s ImageDataGenerator to rescale and normalize image data. I visualized a few random samples from both Organic and Recyclable categories to confirm correct labeling and dataset balance. These preprocessing steps prepared the dataset for training the CNN model.

By the end of Week 1, I had completed environment setup, dataset upload, preprocessing, and data verification. In Week 2, I will focus on building and training the CNN model, plotting accuracy and loss curves, and evaluating its performance on test data.
