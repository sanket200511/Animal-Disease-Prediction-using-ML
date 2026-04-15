# 🐾 Animal Disease Prediction using Machine Learning

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-F37626.svg?&style=for-the-badge&logo=Jupyter&logoColor=white)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-orange?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

## 📌 Overview
Welcome to the **Animal Disease Prediction** project! This repository explores the application of various Machine Learning classification algorithms to predict potential diseases in animals based on symptomatic data. By building and evaluating multiple models, this project aims to identify the most accurate algorithm to assist in early veterinary diagnostics.

## 🧠 Models & Algorithms Implemented
To ensure robust prediction capabilities, the dataset has been trained and tested across 7 different machine learning models. Each algorithm has its own dedicated Jupyter Notebook for clean execution and easy understanding:

| Algorithm | Notebook File |
| :--- | :--- |
| **Random Forest** | [`Random_forest_classifier.ipynb`](./Random_forest_classifier.ipynb) |
| **Gradient Boosting** | [`Gradient_boosting_classifier.ipynb`](./Gradient_boosting_classifier.ipynb) |
| **Decision Tree** | [`Decision_tree_classifier.ipynb`](./Decision_tree_classifier.ipynb) |
| **Support Vector Machine (SVM)** | [`SVM.ipynb`](./SVM.ipynb) |
| **K-Nearest Neighbors (KNN)** | [`KNN.ipynb`](./KNN.ipynb) |
| **Logistic Regression** | [`Logistic_regression.ipynb`](./Logistic_regression.ipynb) |
| **Multinomial Naive Bayes** | [`Multinomial_Naive_Bayes.ipynb`](./Multinomial_Naive_Bayes.ipynb) |

*Note: The general data preprocessing and baseline setup can be found in [`ML_Dataset1.ipynb`](./ML_Dataset1.ipynb).*

## 📂 Repository Structure

```text
📦 Animal-Disease-Prediction-using-ML
 ┣ 📂 Dataset                             # Contains the raw/processed dataset files
 ┣ 📜 Decision_tree_classifier.ipynb      # Decision Tree implementation
 ┣ 📜 Gradient_boosting_classifier.ipynb  # Gradient Boosting implementation
 ┣ 📜 KNN.ipynb                           # K-Nearest Neighbors implementation
 ┣ 📜 Logistic_regression.ipynb           # Logistic Regression implementation
 ┣ 📜 ML_Dataset1.ipynb                   # Primary data exploration & baseline model
 ┣ 📜 Multinomial_Naive_Bayes.ipynb       # Naive Bayes implementation
 ┣ 📜 Random_forest_classifier.ipynb      # Random Forest implementation
 ┗ 📜 SVM.ipynb                           # Support Vector Machine implementation

```
## 🛠️ Tech Stack & Libraries
 * **Language:** Python
 * **Environment:** Jupyter Notebook
 * **Core Libraries:**
   * pandas (Data manipulation)
   * numpy (Numerical computations)
   * scikit-learn (Machine Learning modeling and metrics)
   * matplotlib / seaborn (Data visualization)
## 🚀 How to Run Locally
 1. **Clone the repository:**
   ```bash
   git clone [https://github.com/sanket200511/Animal-Disease-Prediction-using-ML.git](https://github.com/sanket200511/Animal-Disease-Prediction-using-ML.git)
   cd Animal-Disease-Prediction-using-ML
   
   ```
 2. **Install the required dependencies:**
   Make sure you have Python installed. Then, install the required libraries:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn jupyter
   
   ```
 3. **Launch Jupyter Notebook:**
   ```bash
   jupyter notebook
   
   ```
 4. **Run the files:** Open any of the .ipynb files in your browser and execute the cells step-by-step.
## 🤝 Contributing
Contributions, issues, and feature requests are welcome! Feel free to check the issues page if you want to contribute.
 1. Fork the Project
 2. Create your Feature Branch (git checkout -b feature/AmazingFeature)
 3. Commit your Changes (git commit -m 'Add some AmazingFeature')
 4. Push to the Branch (git push origin feature/AmazingFeature)
 5. Open a Pull Request
*If you find this repository helpful for learning about Machine Learning classifiers, please consider giving it a ⭐!*

