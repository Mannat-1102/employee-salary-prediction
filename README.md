# Salary Prediction

## Introduction
This project focuses on predicting employee salaries using various features such as age, gender, education level, job role, and years of experience. We worked with a dataset comprising 6704 entries and 6 attributes to train and evaluate our model.

## Data Preprocessing

### Handling Missing Data
We began by inspecting the dataset for missing values. Any rows containing incomplete information were removed to ensure the model was trained on clean, reliable data.

## Data Visualization


### Top 10 Highest Paying Jobs
![Gender Distribution](https://github.com/Mannat-1102/employee-salary-prediction/blob/45e22f7506557d8cf64112fb2c68a7f648e71709/Top10_Alternate.png
*A Bar plot depicting the highest paying job titles versus the mean salary.*

### Distribution of Continuous Variables
![Age Distribution]https://github.com/Mannat-1102/employee-salary-prediction/blob/45e22f7506557d8cf64112fb2c68a7f648e71709/WhatsApp%20Image%202025-07-28%20at%2017.20.36.jpeg
*This histogram shows the distribution of continuous variables in the dataset.*

### Education and Gender Level Breakdown
![Salary vs. Education]https://github.com/Mannat-1102/employee-salary-prediction/blob/45e22f7506557d8cf64112fb2c68a7f648e71709/age%20exper.jpeg
*A plot displaying the Education Level and Gender.*

### Correlation Heatmap
![Correlation Heatmap]https://github.com/Mannat-1102/employee-salary-prediction/blob/45e22f7506557d8cf64112fb2c68a7f648e71709/Heatmap_Alt.png
*A heatmap illustrating the correlation between different features.*

## Model Development

## Algorithm Selection
We experimented with several machine learning algorithms, including:

Linear Regression
Decision Trees
Random Forest

To fine-tune model performance, we applied GridSearchCV for hyperparameter optimization.

## Model Evaluation
We assessed model performance using the following metrics:

Mean Squared Error (MSE)
Mean Absolute Error (MAE)
Root Mean Squared Error (RMSE)
R-squared (R²)

These metrics helped us evaluate how well each model performed and predicted salaries.


### Feature Importance
![Feature Importance]https://github.com/Mannat-1102/employee-salary-prediction/blob/45e22f7506557d8cf64112fb2c68a7f648e71709/Feature_Importance_Alt.png
*A bar chart depicting the importance of different features in predicting salary.*

## Results

1. Random Forest delivered the best results, with the highest R² and lowest error values, making it the top-performing model.
2. Decision Tree showed decent accuracy but lagged behind Random Forest in terms of error rates..
3. Linear Regression, while simpler, struggled to capture complex patterns and had the lowest performance.


## Conclusion

In conclusion, the Random Forest model demonstrated the best predictive capability for salary estimation in this dataset. Its feature importance analysis revealed the most influential factors.

The Random Forest model stood out as the most accurate and reliable approach for predicting salaries in this dataset. Feature importance analysis further helped identify which factors played the biggest role in determining income.

This project underscores the importance of effective data preprocessing, thoughtful model selection, and rigorous evaluation. The resulting model can be a valuable tool for HR teams, salary benchmarking, and workforce planning

## Usage

To use our salary prediction model, you can follow these steps:

1. Clone this repository.
2. Install the required libraries listed in the `requirements.txt` file.
3. Run the provided Jupyter notebook or Python script to load the model and make predictions on new data.

