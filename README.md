🚔 Crime Category Classification Using Machine Learning & Deep Learning

📌 Project Overview

This project focuses on predicting crime categories using Machine Learning and Deep Learning techniques.

The system analyzes crime-related information, including date, time, district, address, and geographical coordinates, to classify incidents into different crime categories.

The project compares traditional machine learning algorithms with a Convolutional Neural Network (CNN).

🎯 Project Objectives

* Analyze and preprocess crime datasets.
* Explore crime patterns using data visualization.
* Apply feature engineering and dimensionality reduction.
* Train and evaluate multiple classification models.
* Compare model performance using accuracy and other evaluation metrics.

🧠 Machine Learning Models

The following models were implemented:

1. Logistic Regression — A baseline classification algorithm.
2. Support Vector Machine (SVM) — Implemented using SGDClassifier with hinge loss.
3. Decision Tree — A tree-based classification algorithm.
4. Convolutional Neural Network (CNN) — A deep learning model implemented using TensorFlow/Keras.

⚙️ Data Preprocessing

The project includes:

* Handling and preprocessing crime-related features.
* Extracting Year, Month, Day, Hour, Minute, and Weekend information from dates.
* Encoding categorical features.
* Converting address text into numerical features using TF-IDF.
* Applying TruncatedSVD for dimensionality reduction.
* Removing potential data leakage features.

🛠️ Technologies & Libraries

* Python
* Pandas
* NumPy
* Scikit-learn
* TensorFlow / Keras
* Matplotlib
* Joblib
* Jupyter Notebook

📊 Model Evaluation

Models were evaluated using:

* Classification Accuracy
* Classification Reports
* Confusion Matrices
* Accuracy Comparison Plots
* Training Time Comparison

🏆 Results

The CNN achieved the highest reported classification accuracy of 28.72% among the evaluated models.

The results highlight the challenges of multi-class crime classification and provide a comparison between traditional machine learning and deep learning approaches.

🚀 How to Run

1. Download or clone the repository.
2. Install Python and Jupyter Notebook.
3. Install the required libraries:

pip install pandas numpy scikit-learn tensorflow matplotlib joblib notebook

4. Download the required dataset and place train.csv and test.csv in the project directory.
5. Open the Jupyter Notebook and run the cells in order.

📁 Project Files

* Jupyter Notebook: Project implementation and model training.
* Project Report: Documentation, methodology, and evaluation results.
* Dataset: Training and testing data required to reproduce the experiments.

👨‍💻 Developer

Ismail Mohamed

Artificial Intelligence Engineering Student

Interested in Machine Learning, Deep Learning, Robotics, Embedded Systems, and Software Development.
