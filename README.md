# ML-exp4
Regression Analysis: MPG Prediction
📌 Project Overview

This project demonstrates the application of Linear Regression and Polynomial Regression using Machine Learning to predict a vehicle's Miles Per Gallon (MPG) based on its engine displacement.

The project compares a standard Linear Regression model with Polynomial Regression models of different degrees to determine which model provides better prediction performance.

🎯 Objective

The main objectives of this project are:

To understand the working of Linear Regression.
To apply Polynomial Regression for non-linear relationships.
To train and test regression models using a real-world dataset.
To compare model performance using Mean Squared Error (MSE) and R² Score.
To visualize the relationship between engine displacement and fuel efficiency.
📊 Dataset

The project uses the MPG dataset obtained from the Seaborn dataset repository.

The following attributes are selected:

Feature	Description
displacement	Engine displacement
mpg	Miles per gallon / fuel efficiency

Rows containing missing values are removed before training.

🛠️ Technologies Used
Python
Pandas
NumPy
Matplotlib
Scikit-learn
Google Colab / Jupyter Notebook
🤖 Machine Learning Models
1. Linear Regression

Linear Regression is used as the baseline model to predict MPG from engine displacement.

The dataset is divided into training and testing sets using an 80:20 split.

Performance:

MSE: 18.1025
R² Score: 0.6633
2. Polynomial Regression

Polynomial Regression is applied with degrees 2, 3, and 4 to model a possible non-linear relationship between displacement and MPG.

Model	MSE	R² Score
Linear Regression	18.1025	0.6633
Polynomial Degree 2	15.1074	0.7190
Polynomial Degree 3	14.9436	0.7221
Polynomial Degree 4	14.9615	0.7217

The Degree 3 Polynomial Regression model provides the best performance among the tested models based on the lowest MSE and highest R² score.

📈 Visualization

The project visualizes:

Original data points
Linear Regression line
Polynomial Regression curves for degrees 2, 3, and 4

This helps compare how different regression models fit the relationship between engine displacement and MPG.

🔄 Project Workflow
Dataset
   ↓
Data Loading
   ↓
Column Selection
   ↓
Missing Value Removal
   ↓
Feature & Target Selection
   ↓
Train-Test Split
   ↓
Linear Regression
   ↓
Polynomial Regression
   ↓
Model Evaluation
   ↓
Visualization
   ↓
Performance Comparison
📁 Project Structure
Regression-Analysis/
│
├── ML4(1).ipynb
└── README.md
📌 Results

The experimental results show that Polynomial Regression performs better than standard Linear Regression for this dataset.

Among the tested polynomial degrees, Degree 3 achieved the best result, with an MSE of approximately 14.94 and an R² score of approximately 0.722.

🚀 Conclusion

This project demonstrates how regression algorithms can be used to predict a continuous numerical value. The comparison shows that a polynomial model can capture the relationship between engine displacement and MPG more effectively than a simple linear model for this dataset.

👩‍💻 Author

Mithika Biju

B.Tech Computer Science and Engineering
