Music Album Popularity Prediction Using Machine Learning

Overview

This project focuses on predicting the popularity of music albums using various machine learning algorithms. Leveraging a dataset sourced from Kaggle containing audio features (e.g., danceability, energy, tempo, acousticness) and album metadata, the study compares performance across multiple models to determine the best predictors.

Algorithms Compared

Linear Regression

K-Nearest Neighbors (KNN)

Support Vector Machine (SVM)

Random Forest

Artificial Neural Networks (ANN)

CatBoost

Logistic Regression

Graph Neural Network (GNN)

Key Findings

Random Forest and Graph Neural Networks generally outperform simpler models like Logistic Regression and SVM, achieving accuracies above 89%.

Statistical analysis using independent sample t-tests evaluates significance between model performances.

Ensemble and deep learning models handle complex, nonlinear data better, making them valuable for real-world music industry applications.

Dataset

Source: Kaggle

Size: 600+ instances

Features: 20 audio-based and metadata attributes including tempo, energy, danceability, acousticness, and release year.

Project Structure

notebooks/ — Jupyter notebooks implementing each algorithm and analysis

data/ — Raw and preprocessed dataset files

outputs/ — Generated prediction results and visualizations

presentation/ — Slides summarizing methodology, results, and conclusions

README.md — Project description and guide

Installation

Install required packages using:
pip install -r requirements.txt

Usage

Open and run the Jupyter notebooks in the notebooks/ folder to explore data preprocessing, model training, evaluation, and comparative analysis.

Visualizations and detailed results are available in the outputs/ folder.

Contributing

Contributions are welcome! Feel free to fork the repository, open issues for bugs or feature requests, and submit pull requests.

References

Romero et al., 2021 – AI in Music and Sound

Schedl et al., 2014 – Music Information Retrieval

Wilkes et al., 2021 – Audio and Visual Analysis for Music Genre Recognition

Chen et al., 2018 – Nearest Neighbor Methods in Prediction

Additional citations in project documentation

License

This project is licensed under the MIT License.
