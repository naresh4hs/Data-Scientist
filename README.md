
---

# Wine Classification Analysis

## Introduction
This Jupyter Notebook file contains code for a wine classification task using the Wine Quality dataset. The analysis focuses on utilizing various machine learning models to classify wine quality based on input features.

### Libraries Used:
- numpy
- pandas
- sklearn.datasets
- sklearn.model_selection.train_test_split
- sklearn.svm.SVC
- sklearn.linear_model.LogisticRegression
- sklearn.ensemble.RandomForestClassifier
- sklearn.metrics.accuracy_score

### Setup:
1. Ensure you have Jupyter Notebook installed.
2. Install required libraries by running the following commands:

    pip install numpy pandas scikit-learn


### Dataset:
The code utilizes the Wine Quality dataset, specifically the 'winequality-red.csv' file

### Running the Code:
1. Download the 'Wine_Classification.ipynb' file
2. Place the dataset file in the same directory as the notebook or specify the correct path in the code.
3. Open Jupyter Notebook.
4. Upload the downloaded 'Wine_Classification.ipynb' file to your Jupyter environment.
5. Run each cell in the notebook sequentially. The code loads the dataset from the specified path.
6. Utilize sklearn's machine learning models such as SVC, Logistic Regression, and Random Forest Classifier to perform classification on wine quality.
7. Evaluate the models using accuracy_score and other relevant metrics to determine their performance.

### Important Notes:
- **Dataset:** The dataset contains information about wine quality. Ensure the dataset file is accessible and correctly loaded.
- **Model Evaluation:** Use accuracy_score and other metrics to evaluate the performance of classification models.
