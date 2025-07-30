# Linear-Regression-from-Scratch-using-Gradient-Descent
Welcome to this project where we implement Linear Regression from scratch using only NumPy and Matplotlib, and optimize the parameters using the Gradient Descent algorithm. This notebook is designed for students and enthusiasts who want to deeply understand how gradient-based optimization works behind the scenes of machine learning models.

## The provided code demonstrates the application of gradient descent for optimizing a linear regression model with polynomial features on the "insurance.csv" dataset.
* It performs the following tasks:
  - Loads the **insurance.csv** dataset, which contains information about BMI (Body Mass Index) and insurance charges.
  - Selects the "bmi" feature as the independent variable (X) and the "charges" column as the dependent variable (y).
  - Splits the data into training and testing sets, with 80% of the data used for training and 20% for testing.
  - Creates polynomial features of degree 1 (linear regression) using the PolynomialFeatures class from scikit-learn.
  - Initializes parameters for gradient descent, including the learning rate (alpha), the number of iterations, and the model's coefficients (theta).
  - Performs gradient descent optimization to find the optimal parameters for the linear regression model.
  - Displays the cost (mean squared error) at regular intervals to monitor the optimization progress.
  - Sorts the training data for plotting.
  - Generates predictions using the trained model and sorted data.
  - Creates a scatter plot of the dataset with violet data points and black outlines.
  - Plots the learned linear regression line in red.
## 🚀 Workflow:
* Dataset Creation:
  - A synthetic dataset is generated using NumPy for clarity and control.
  - Visualization of data distribution.
* Linear Regression Implementation:
  - Hypothesis function: y=mx+c
  - Loss Function: Mean Squared Error
  - Manual implementation of gradient descent to optimize m (slope) and c (intercept).
* Training Loop:
  - Iterative update of parameters.
  - Loss tracking over epochs.
  - Visualization of convergence.
* Result Evaluation:
  - Final parameters.
  - Comparison of original data vs predicted line.
  - Loss curve plot to show how the model improves.
## 🧠 What You'll Learn
  - The mathematical intuition behind Linear Regression.

  - How cost functions work in regression tasks.

  - How to implement the Gradient Descent algorithm manually.

  - Visualizing model performance using plots and loss curves.
## 📈 Visual Outputs
  - ✅ Scatter plot of the data

  - ✅ Predicted regression line overlay

  - ✅ Loss curve showing convergence
## 🛠️ Technologies Used
  - Python 3

  - NumPy

  - Matplotlib

  - Jupyter Notebook
## 🤝 Contributing
Feel free to open issues or submit pull requests if you have suggestions or want to improve the project. Let’s build better ML understanding together!
## 📄 License
This project is licensed under the MIT License.
## Author
* Manjul Mayank


