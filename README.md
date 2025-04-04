# Healthcare-Prediction-on-Diabetes-Patients

This project focuses on predicting diabetes using machine learning techniques such as Logistic Regression, Random Forest, Decision Tree Classifier, KNeighborsClassifier , Support Vector Machine (SVM), and Gradient Boosting.

## 📌 Features

Data Preprocessing: Handling missing values, scaling, encoding.

Exploratory Data Analysis (EDA): Using Sweetviz for automated visualization.

Model Training & Evaluation: Logistic Regression, Random Forest, Decision Tree Classifier, K-Neighbors Classifier, SVM, Gradient Boosting.

Performance Metrics: Accuracy, Precision, Recall, F1-score, ROC Curve, and AUC.

Hyperparameter Tuning: Using GridSearchCV for optimization.

## 📂 Dataset

The dataset used in this project is health_care_diabetes.csv, containing various patient health indicators to predict diabetes.

## 🚀 Installation & Setup

Clone the repository:

```
git clone https://github.com/your-username/your-repo.git 
```

Navigate to the project directory:

```
cd your-repo
```

Install the required dependencies:
```
pip install -r requirements.txt
```

Run the Jupyter Notebook or Python script to train and evaluate the model.

## 📊 Model Performance

| Model | Accuracy | AUC |
|--|---|---|
| Logistic Regression | 75% |0.78|
| Random Forest |76% |0.80 |
|Decision Tree|72%|0.75|
|KNeighborsClassifier |70%|0.73|
|Support Vector Machine (SVM) |73% |0.77|
|Gradient Boosting |78% |0.82|

## Model Comparsion
<img src="https://github.com/user-attachments/assets/369ccc67-a656-4e4b-af65-03461495e2d6">


## 📖 Viewing the Notebook

If the notebook does not render on GitHub, use Nbviewer:
```
https://nbviewer.org/github/your-username/your-repo/blob/main/your_notebook.ipynb
```
Replace your-username, your-repo, and your_notebook.ipynb accordingly.

## 🛠 Troubleshooting

### Fix Notebook Rendering Issue

Run the following command to clean metadata before pushing to GitHub:
```
jupyter nbconvert --ClearMetadataPreprocessor.enabled=True --to notebook --inplace your_notebook.ipynb
```
### Sweetviz Issue (ModuleNotFoundError)

If Sweetviz is not working, reinstall it:
```
pip install sweetviz --user
```
## 🤝 Contribution

Feel free to fork the repository and submit a pull request if you find any improvements!
