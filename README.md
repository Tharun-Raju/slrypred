# salarypred
This is a simple linear regression model used to predict salary with years of experience, the accuracy is not great as there was only 30 rows of data in the dataset



Linear Regression Model for Salary Prediction Based on Years of Experience
This repository contains a simple implementation of a linear regression model to predict salaries based on years of experience. The model is built using Python and scikit-learn, and is intended to demonstrate how to perform basic regression analysis on a dataset.


Project Overview
The goal of this project is to build a predictive model that estimates the salary of an individual based on their years of experience. The process includes:

Loading and preprocessing the dataset.

Training a linear regression model.

Evaluating the model's performance using key metrics.

Visualizing the relationship between experience and salary.

Testing the model by predicting salaries for given years of experience.

Key Features:

Data Preprocessing: Handles missing values, removes unnecessary columns (e.g., 'Unnamed: 0'), and splits the data into training and testing sets.

Model Training: Utilizes the scikit-learn LinearRegression class to fit the model to the training data.

Model Evaluation: Calculates performance metrics such as Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and the R² Score to assess the model's accuracy.

Visualization: Includes plots to visualize the training and testing results, actual vs. predicted salaries, and residual distributions.

Prediction Functionality: Allows users to input a specific number of years of experience to get a predicted salary using the trained model.

Installation and Usage:
Clone the Repository:
git clone https://github.com/Tharun-Raju/slrypred.git

Install Dependencies:
pip install -r requirements.txt

Run the Model: Modify the main.py file to input your desired years of experience, then run the script to see the predicted salary.

years_of_experience = 5
predicted_salary = model.predict(np.array([[years_of_experience]]))
print(f"Predicted Salary for {years_of_experience} years of experience: ${predicted_salary[0]:,.2f}")

Visualize Results: Execute the script to see visualizations of the model's predictions vs. actual salaries, and assess the model's performance.

Repository Structure
Salary_dataset.csv: The dataset containing years of experience and corresponding salaries.
main.py: The main script for training, evaluating, and testing the linear regression model.
requirements.txt: A list of Python dependencies required to run the project.


Contributions
Contributions, issues, and feature requests are welcome! Feel free to check the issues page or submit a pull request.
Contributions, issues, and feature requests are welcome! Feel free to check the issues page or submit a pull request.
