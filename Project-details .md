Rock vs Mine Prediction using Machine Learning.

👉Project Overview :-

This project focuses on building a binary classification machine learning model to predict whether an object detected by sonar signals is a Rock or a Mine.
Such problems are common in defense, naval systems, and underwater exploration, where accurate classification is critical.


👉Problem Statement 

Given sonar signal data (numerical features), classify the object as:
Rock (R)
Mine (M)

👉Dataset Description

Dataset: -<a href="https://github.com/rajankumar-1439/rock-vs-mine-prediction-using-machine-learning/blob/main/Sonar%20dataset.csv">Sonar dataset </a>

Total samples: 208

Features: 60 numerical attributes (sonar energy values)

Target column:

R → Rock

M → Mine

📊 Machine Learning Workflow:-

The project follows a standard ML pipeline:

Data Loading

 -Dataset loaded using pandas

Data Exploration

 -Shape, value distribution, and class balance checked

Feature & Target Separation

 -Independent variables (X)
 -Dependent variable (y)

Train-Test Split

 -Data split into training and testing sets
 -Stratified split used to maintain class balance

Model Training

 -Classification model trained on training data

Model Evaluation

 -Accuracy score calculated on both train and test data

Prediction

 -Model used to predict unseen sonar input

🛠️Technologies & Libraries Used

 -Python
 
 -NumPy
 
 -Pandas
 
 -Scikit-learn

👉Model Used

Logistic Regression

Why Logistic Regression?

 -Suitable for binary classification
 
 -Works well with numerical features
 
 -Easy to interpret
 
 -Fast and efficient for small-to-medium datasets

 📈 Model Performance
 
Training Accuracy: Displayed in notebook

Testing Accuracy: Displayed in notebook

⚠️ Note:
Accuracy may vary depending on random state and data split. This project focuses on learning and implementation, not production-level optimization.

👉How to Run the Project:-
Clone the repository

git clone -<a href="https://github.com/rajankumar-1439/rock-vs-mine-prediction-using-machine-learning/blob/main/Rock%20vs%20mine%20prediction..ipynb">repository</a>

🧾Project Structure

  sonar-rock-mine-classifier/
  │
  ├── Rock vs mine prediction.ipynb
  ├── README.md

👉Key Learnings

 -Understanding binary classification problems
 
 -Proper train-test splitting with stratification
 
 -Handling numerical datasets
 
 -Model training and evaluation using scikit-learn
 
 -Writing clean and readable ML code
  
👉Future Improvements

Be honest — this project is basic. To level it up:

 -Try other classifiers (SVM, Random Forest, KNN)
 
 -Perform feature scaling
 
 -Add confusion matrix and classification report
 
 -Convert notebook into a web app (Flask / Streamlit)

 
👤 Author

Rajan Kumar

📧 rajankumarmu1439@gmail.com
