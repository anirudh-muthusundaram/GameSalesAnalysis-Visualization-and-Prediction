# Unlocking Game Success: Advanced Data Visualization and Predictive Modeling with Five Cutting-Edge ML Techniques Using Video Game Sales Data

Problem Statement: The video game industry is a rapidly evolving and highly competitive market. Predicting the sales of video games is a complex task influenced by various factors such as genre, platform, target age group, and user and critic reviews. Accurately forecasting these sales is crucial for developers to understand their audience better and optimize profit margins. This project aims to build a predictive model that provides insights into the factors affecting game sales, enabling developers to make informed decisions.

Machine Learning Models Used: To achieve accurate predictions, the following regression models were implemented and evaluated:

Decision Trees Regressor
Random Forest Regressor
Support Vector Machines (SVR)
Neural Networks (Basic Sequential Model)
Gradient Boosting Regressor
Key Features: The dataset's most influential features correlated with global sales include regional sales figures (NA_Sales, EU_Sales, JP_Sales, Other_Sales), Critic_Score, Critic_Count, and User_Count. These features were used to predict global sales, with the models trained and tested using a 75/25 split.

Evaluation Metrics: Since the project deals with regression, the models were evaluated using the following metrics:

Mean Squared Error (MSE): Measures the average squared difference between predicted and actual values, with a lower MSE indicating better model performance.
Mean Absolute Error (MAE): Calculates the average absolute difference between predicted and actual values, giving equal weight to all errors.
R Squared Score (R²): Represents the proportion of variance in the dependent variable explained by the independent variables, with values closer to 1 indicating a better fit.
Findings:

The Decision Tree Regressor was used to understand the decision-making steps involved in predicting global sales.
The Random Forest Regressor improved performance by averaging the results of multiple decision trees, showing lower error rates and higher R² scores.
The Support Vector Regressor (SVR), especially with a radial basis function kernel, provided robust predictions but required careful tuning to avoid overfitting.
Neural Networks modeled complex relationships, though they exhibited signs of overfitting, suggesting they may not be the best fit for this dataset.
The Gradient Boosting Regressor showed strong performance by iteratively correcting errors in previous predictions, making it a powerful model for this task.
Conclusion: This project successfully demonstrated the use of various regression models to predict video game sales. Through model evaluation and tuning, the project provided valuable insights into the factors influencing sales, offering a potential tool for game developers to optimize their market strategies.