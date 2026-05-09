# Wine Quality Predictor 🍷📊
This data science project explores the chemical properties of wine to predict its overall quality rating. By applying multiple Machine Learning algorithms, this repository demonstrates a complete workflow from exploratory data analysis (EDA) to model evaluation and selection.

# 📌 Project Overview
The objective of this project is to determine which chemical features (such as acidity, residual sugar, and alcohol content) have the highest impact on wine quality. To find the most accurate predictive model, three different algorithms were trained, evaluated, and compared.

Ultimately, the Random Forest Regressor outperformed the others, proving to be the most highly capable of predicting the continuous quality scores.


# 🧠 Models Evaluated
Support Vector Machine (SVM): Used to attempt finding a hyperplane that distinctly classifies the quality levels.

Naive Bayes: A probabilistic approach tested for baseline classification performance.

Random Forest Regressor : An ensemble learning method that successfully captured the complex, non-linear relationships between the chemical inputs and the final quality score.

# 🛠️ Tech Stack & Libraries
Language: Python 

Data Manipulation: pandas, numpy

Machine Learning: scikit-learn (for SVM, Naive Bayes, and Random Forest implementations)

Data Visualization: matplotlib, seaborn (for feature correlation heatmaps and distribution plots)


# 📂 Repository Structure

Data_Science_Major_Project.ipynb : Colab notebook containing the EDA, data preprocessing, and model comparison steps.

upload_b17b4ebe-b5ef-4168-b23e-759428717a8b.csv : The wine quality dataset.

README.md: Project documentation.
