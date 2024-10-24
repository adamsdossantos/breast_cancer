# Breast Cancer Classification with Logistic Regression 

## 1. Project Overview

This project implements a Logistic Regression model to classify whether a tumor is benign or malignant based on various diagnostic features. The model is trained using the famous Breast Cancer Wisconsin dataset, where the goal is to predict the malignancy of the cancer based on input features like mean radius, texture, perimeter, and area.


## 2. Dataset Source

https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data

## 3. Features
- **Data Preprocessing**: Data  cleaning, scaling, and splitting into training and test sets.
- **Model Training**: Training a Logistic Regression model to classify cancerous tumors.
- **Model Evaluation**: Evaluating the model's performance using metrics like accuracy, precision, recall, F1-score, and ROC-AUC score.
- **Visualization**: Visualization of the model’s performance using confusion matrix and ROC curves.



## 4. Project Structure
    ├── data.csv                    # Dataset file 
    ├── breast_cancer.ipynb         # Jupyter notebook with end-to-end implementation
    ├── README.md                   # Project documentation
    ├── requirements.txt            # Python dependencies
    └── .gitignore                  # Files to be ignored in version control

## 5. Getting Started

### Prerequisites
- Python 3.9 or higher
- Jupyter Notebook
- scikit-learn
- pandas
- matplotlib
- numpy

### Installation
1. Clone the repository:

```python
    git clone https://github.com/adamsdossantos/breast_cancer.git
    
```
2. Create a virtual environment and activate it:
```python
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```

3. Install the required packages:
```python
   pip install -r requirements.txt
```

4. Launch the Jupyter Notebook:
```python
    jupyter notebook breast_cancer.ipynb
```
## 6. Usage

Open the breast_cancer.ipynb file and follow the step-by-step instructions provided in the notebook. The notebook includes:

- **Data Loading and Preprocessing**: Load data from the 'data.csv' and perform necessary preprocessing like handling missing values, encoding categorical variables, and feature scaling.
- **Model Training**: Train a Logistic Regression model using scikit-learn to classify tumors as benign or malignant.
- **Model Evaluation**:  Evaluate the model's performance using accuracy, precision, recall, F1-score, and ROC-AUC metrics. A confusion matrix will be used to assess the true positive, true negative, false positive, and false negative rates.
- **Visualization**:  Visualize the confusion matrix and the ROC curve to understand the classifier's performance.


## 7. Results in Test

| Metric    |  Value |
|-----------|--------|
| Accuracy  |  94%   |
| Precision	 |  94%   |
| Recall   | 92%|
| F1-score |    94%|
|ROC-AUC | 92% |




## 8. Contributing

Feel free to open issues or submit pull requests if you find any bugs or want to improve the project.

## 9. License

This project is licensed under the MIT License - see the LICENSE file for details.







