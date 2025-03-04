# Salary-Prediction

This code demonstrates the application of simple linear regression using Python and essential data science libraries such as NumPy, pandas, scikit-learn, matplotlib, and pickle. The dataset Salary_Data.csv is loaded using pandas, where it contains two columns: years of experience (independent variable) and salary (dependent variable). The data is split into training and test sets in an 80-20 ratio using train_test_split. This ensures that the model is trained on the majority of the data and evaluated on unseen data, simulating real-world conditions.

A Linear Regression model is then trained using the training set (X_train, y_train) and fitted to the data using regressor.fit(). The trained model is used to predict salaries for the test set (X_test), allowing us to assess its performance.

To visualize the model’s performance, scatter plots of both the training and test sets are generated using matplotlib.pyplot, where actual salaries are compared to predicted salaries using a regression line. This visualization helps in understanding how well the linear model fits the data.

The model's performance is further evaluated using the R-squared score (coefficient of determination) and mean squared error (MSE) for both training and test sets. These metrics provide insight into the model’s accuracy and generalization ability. The MSE highlights the average squared difference between actual and predicted salaries.

Additionally, the model is used to predict salaries for specific values (12 and 20 years of experience), showcasing how it can be applied to new data.

Finally, the trained model is serialized using Python’s pickle module and saved as linear_regression_model.pkl, allowing future use without retraining. This project applies essential machine learning skills, including data preprocessing, model training, evaluation, visualization, and model persistence, all critical for building data-driven solutions in real-world scenarios.
