
# 🩺 Diabetes Prediction Case Study

## 📜 Overview
This project focuses on predicting the likelihood of diabetes in patients using various machine learning algorithms. The dataset used contains several medical predictor variables and a target variable indicating whether the patient has diabetes.

## ⚙️ Algorithms Used
We implemented and compared the following machine learning algorithms:

1. **🌳 Decision Tree**
2. **🔗 Logistic Regression**
3. **🔍 K-Nearest Neighbors (KNN)**
4. **🌲 Random Forest**

## 🗂️ Dataset
- **Source**: [Pima Indians Diabetes Dataset](https://www.kaggle.com/uciml/pima-indians-diabetes-database)
- **Features**:
  - `Pregnancies`: Number of times pregnant
  - `Glucose`: Plasma glucose concentration
  - `BloodPressure`: Diastolic blood pressure (mm Hg)
  - `SkinThickness`: Triceps skin fold thickness (mm)
  - `Insulin`: 2-Hour serum insulin (mu U/ml)
  - `BMI`: Body mass index (weight in kg/(height in m)^2)
  - `DiabetesPedigreeFunction`: Diabetes pedigree function
  - `Age`: Age (years)
- **Target**:
  - `Outcome`: 0 (No Diabetes), 1 (Diabetes)

## 🖥️Usage
To run each algorithm, navigate to the directory and execute the corresponding Python file.
<br>For example:
   
    python DiabetesDTree.py

## 📊 Results

| Algorithm               | Training Accuracy | Test Accuracy |
|-------------------------|-------------------|---------------|
| 🌳 Decision Tree         | 0.78              | 0.76          |
| 🔗 Logistic Regression   | 0.79              | 0.77          |
| 🔍 K-Nearest Neighbors   | 0.75              | 0.74          |
| 🌲 Random Forest         | 0.81              | 0.79          |

##  📋Requirements
🐍 **Python 3.x**<br>
Required Libraries: <br>
🧪 **scikit-learn**<br>
🧮 **numpy**<br>
🗃 **pandas**<br>
📊 **matplotlib**<br>
You can install the required libraries using the following command:
               
      pip install -r requirements.txt

## 📈 Visualizations
The project also includes several visualizations to help understand the data and the performance of each model:

<b>Correlation Heatmap:</b> Shows the relationship between features.<br>
<b>ROC Curve:<b> Plots the true positive rate against the false positive rate for each model.<br>
<b>Confusion Matrix:<b> Provides a summary of the prediction results on the test data.<br>
## 📊Conclusion
This case study demonstrates the application of various machine learning algorithms to the Diabetes dataset. By comparing the accuracy of different models, we can evaluate their effectiveness for this classification task.<br><br>

The Random Forest algorithm provided the best performance on this dataset, with the highest test accuracy. However, logistic regression is a strong contender due to its interpretability and simplicity.


This file will give users an understanding of the project, the algorithms I have implemented, and how to run your code.
