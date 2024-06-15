# IPL Score Prediction

## Project Description

This project predicts the first innings score in IPL matches using machine learning techniques.

## Methods Used

- Linear Regression
- Ridge Regression
- Flask web development


## Components
- Data Preprocessing:

Data Cleaning: Cleaning and preprocessing IPL match data to ensure consistency and relevance. This includes removing unnecessary columns, filtering consistent teams and relevant stadiums, converting data types, and handling missing values.
Feature Engineering: Creating new features or transforming existing ones to improve predictive performance. For instance, deriving features like runs scored and wickets taken in the last 5 overs.
One-Hot Encoding: Converting categorical variables like venue and team names into numerical format for machine learning model compatibility.

- Machine Learning Model:

Ridge Regression: Using Ridge Regression, a linear regression model that incorporates regularization to prevent overfitting, to predict the first innings score. Hyperparameter tuning is performed using RandomizedSearchCV to find the optimal regularization parameter (alpha).
Model Training and Evaluation: Splitting the dataset into training and testing sets, training the Ridge Regression model on the training data, and evaluating its performance using metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared (R²) score.

- Web Application Development:

Flask: Utilizing Flask, a lightweight web framework for Python, to build the web application.
HTML/CSS: Creating an HTML user interface (UI) styled with CSS for user interaction.
JavaScript: Adding client-side validation using JavaScript to ensure form data integrity before submission.
Deployment: Running the Flask app locally to serve predictions on the web interface.

## How to Use

1. Clone the repository.
2. Set up Python environment with required dependencies.
3. Run `app.py` to start the Flask web application.
4. Access the web application in your browser.

## Repository Structure

- `app.py`: Flask web application script.
- `data/`: Directory containing IPL dataset.
- `models/`: Directory containing trained machine learning models.
- `templates/`: HTML templates for web interface.
- `static/`: CSS and JavaScript files for styling and interactivity.
