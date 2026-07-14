# VedGrow_ML_01 - Iris Flower Classification

A Machine Learning classification project that predicts the species of an Iris flower using its sepal and petal measurements. The project compares the performance of three popular classification algorithms using the classic Iris dataset from scikit-learn.

## Features

* Load and explore the Iris dataset
* Perform Exploratory Data Analysis (EDA)
* Visualize feature relationships with Pairplot
* Display Correlation Heatmap
* Visualize feature distributions using Boxplots
* Train multiple Machine Learning models:

  * K-Nearest Neighbors (KNN)
  * Decision Tree Classifier
  * Support Vector Machine (SVM)
* Compare models using:

  * Accuracy
  * Precision
  * Recall
  * F1-Score
* Generate Confusion Matrix for each model
* Predict the species for custom flower measurements

## Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn

## Project Structure

```
Iris-Flower-Classification/
│── notebooks/

│     └── iris_classification.ipynb

│── images/

│── requirements.txt

│── README.md
```

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/VedGrow_ML_01.git
```

Navigate to the project folder:

```bash
cd VedGrow_ML_01
```

Install the required packages:

```bash
pip install -r requirements.txt
```

## Run the Project

open the Jupyter Notebook:

```bash
jupyter notebook notebooks/iris_classification.ipynb
```

## Model Performance

The project compares the following classifiers:

* KNN
* Decision Tree
* SVM

Evaluation Metrics:

* Accuracy
* Precision
* Recall
* F1-Score

## Sample Prediction

Input:

```
Sepal Length = 5.1
Sepal Width = 3.5
Petal Length = 1.4
Petal Width = 0.2
```

Predicted Output:

```
Setosa
```

## Future Improvements

* Hyperparameter tuning using GridSearchCV
* Cross-validation
* Model serialization using Pickle
* Web application using Flask or FastAPI
* Interactive dashboard using Streamlit

## Author

Shantanu Kumar Sharma
