# **SCC.222 Coursework: Machine Learning Classifiers**

This repository contains my submission for the SCC.222 coursework, focusing on the implementation, evaluation, and comparison of three distinct machine learning classifiers: **K-Nearest Neighbors (KNN)**, **Naive Bayes (NB)**, and **Decision Trees (DT)**.


## **📊 Dataset**

The project uses the **Glass Identification Database** (sourced from the UCI Machine Learning Repository). The dataset contains attributes of various glass samples and aims to classify them into different types based on their chemical composition.

- **Location:** dataset/glass.data (Data), dataset/glass.names (Metadata/Attribute Information)

- **Features:** Refractive Index (RI) and 8 weight percentages of corresponding oxides (Na, Mg, Al, Si, K, Ca, Ba, Fe).

- **Target:** Type of glass (e.g., building windows, vehicle windows, containers, tableware, headlamps).


## **📁 Repository Structure**

- dataset/: Directory containing the raw Glass Identification dataset and its accompanying metadata files.

- main.ipynb: The main Jupyter Notebook containing all Python code for data loading, exploratory data analysis (EDA), preprocessing, model training, hyperparameter tuning, and evaluation.

- report.pdf: A comprehensive written report detailing the methodology, experimental setup, results, and critical analysis of the three classifiers' performances.

- LICENSE: The license under which this project is distributed.


## **🚀 Getting Started**

### **Prerequisites**

To run the notebook, you will need Python 3 installed along with the following libraries:

- pandas

- numpy

- scikit-learn

- matplotlib

- seaborn

- jupyter

You can install these dependencies using pip:

pip install pandas numpy scikit-learn matplotlib seaborn jupyter


### **Running the Code**

1. Clone this repository to your local machine:\
   git clone \[https\://github.com/vali-hameed/knn-nb-and-dt.git]\(https\://github.com/vali-hameed/knn-nb-and-dt.git)\
   cd knn-nb-and-dt

2. Launch Jupyter Notebook:\
   jupyter notebook

3. Open main.ipynb in your browser and run the cells sequentially to reproduce the experiments.


## **📈 Methodology & Models**

The Jupyter Notebook (main.ipynb) covers:

1. **Data Preprocessing:** Handling missing values (if any), scaling features, and splitting the data into training and testing sets.

2. **K-Nearest Neighbors (KNN):** Implementation and hyperparameter tuning for 'k' and distance metrics.

3. **Naive Bayes (NB):** Implementation using Gaussian Naive Bayes appropriate for continuous feature distributions.

4. **Decision Tree (DT):** Implementation and tuning of tree depth, splitting criteria (Gini vs. Entropy).

5. **Evaluation:** Comparing models using metrics such as Accuracy, Precision, Recall, F1-Score, and Confusion Matrices.

For a detailed analysis of the results, please refer to report.pdf.
