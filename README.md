# Sonar_Rock_vs_Mine_Classification

  A Machine Learning project that classifies sonar signals as either a Rock or a Mine using Logistic Regression.
  This project demonstrates a complete end-to-end ML workflow, starting from data preprocessing to building a predictive system for real-time classification.

Problem Statement

  Sonar signals reflected from objects underwater can be analyzed to determine whether the object is:

    Rock (R)
    Mine (M)

The goal of this project is to train a Machine Learning model capable of accurately classifying these signals.

Machine Learning Workflow

The notebook covers the full ML pipeline:

  1. Importing libraries
  2. Loading the dataset
  3. Exploratory data analysis (EDA)
  4. Feature and label separation
  5. Train-test split
  6. Feature scaling using StandardScaler
  7. Model training with Logistic Regression
  8. Model evaluation using accuracy score
  9. Building a predictive system

Technologies Used

  Python
  NumPy
  Pandas
  Scikit-learn
  Jupyter Notebook

Project Structure

  ─ Sonar ML Model.ipynb
  ─ sonar data.csv
  ─ README.md

Model Used

  This project uses:

    train_test_split: for dataset splitting
    StandardScaler: for feature normalization
    Logistic Regression: for binary classification
    accuracy_score: for performance evaluation

Results

  The model achieves strong performance on both training and testing datasets.

Typical workflow outputs:

  Training Accuracy: 90.9%
  Testing Accuracy: 85.71%
  This confirms that the model generalizes well for this dataset.

Example Prediction

  The notebook includes a predictive system where custom sonar signal values can be entered as input.

Key Learning Outcomes

  Through this project, the following ML concepts are demonstrated:

    Data preprocessing

    Feature scaling

    Binary classification

    Model evaluation

    Real-world prediction workflow

    Clean ML pipeline design (which it is the first time I do it)

    Future Improvements

    Try advanced models like SVM

Credits
  Based on Siddhardhan's YouTube tutorial with personal modifications including StandardScaler, stratify=y and Using some Functions to keep Clean Code.

Author

  Belal Moustafa Mohamed
  Naval Architecture & Marine Engineering student exploring AI, Machine Learning, and Cloud Computing.
