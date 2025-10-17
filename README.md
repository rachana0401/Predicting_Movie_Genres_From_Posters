# Movie Genre Prediction from Posters

##  Overview
This project aims to **predict the genres of a movie from its poster image** using **machine learning and deep learning techniques**.  
By training a CNN-based model on a dataset of movie posters and their associated genres, the system learns to extract visual features that correlate with genre characteristics such as color, texture, and design patterns.

---

##  Project Pipeline
1. **Data Collection & Preprocessing**
   - Dataset of movie posters with corresponding genre labels downloaded from Kaggle 
   - Image resizing, normalization, and label encoding.
   - Exploratory Data Analysis (EDA) for class distribution, visual trends, etc.
   - Implemented in [`Data Preprocessing_EDA.ipynb`](./Data%20Preprocessing_EDA.ipynb).

2. **Model Configuration & Training**
   - Transfer learning using a CNN model - ResNet50 
   - Train–validation split and augmentation for better generalization.
   - Evaluation using precision, recall, AUC curve and confusion matrix.
   - Implemented in [`Model Config_Training.ipynb`](./Model%20Config_Training.ipynb).

3. **Genre Prediction**
   - The trained model predicts probable genres given a new movie poster.
   - Supports multi-label classification if a movie belongs to multiple genres.

---

##  Evaluation Metrics 
- AUC Curve, Precision, Recall, F1-Score   
- Training vs. validation loss and accuracy plots
- Accuracy

---

