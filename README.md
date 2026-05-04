# RealOrFakeReviewDetection

Overview

This project focuses on detecting whether online reviews are real or fake using machine learning techniques. The model is trained on a hybrid dataset consisting of real Yelp reviews and synthetically generated fake reviews.

Technologies Used
Python
Scikit-learn
Pandas
NumPy
Google Colab
Dataset

This project uses a hybrid dataset:

Real reviews sourced from the Yelp Open Dataset
Synthetic fake reviews generated programmatically

The final datasets used for training and testing are:

yelp_train_exp.csv
yelp_test_exp.csv

The original Yelp dataset is not included due to size constraints. It can be downloaded from:
https://www.yelp.com/dataset

How to Run:

-Open the notebook in Google Colab

-Upload the dataset files (yelp_train_exp.csv, yelp_test_exp.csv)

-Run all cells

Models Used:

-Logistic Regression

-Decision Tree

Results:
-The models were evaluated on their ability to distinguish between real and fake reviews.

-Logistic Regression achieved higher accuracy and more consistent performance.
Decision Tree showed lower accuracy and was more prone to overfitting

Overall, Logistic Regression proved to be the more reliable model for this classification task.

Key Insight:

Fake reviews tend to follow repetitive patterns and lack the variability found in real human-written reviews. Machine learning models are able to detect these subtle differences effectively.

Future Improvements:

-Use larger and more diverse datasets

-Experiment with advanced models (e.g., Neural Networks)

-Incorporate NLP techniques such as TF-IDF or word embeddings

The project evaluates model performance using accuracy and classification metrics to distinguish between real and fake reviews.

Authors

Adnan Bajalan, Saja Bushara, Coda Richmond, and Giselle Lechuga
