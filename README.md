# Salary Prediction

## Introduction
This project focuses on predicting employee salaries using various features such as age, gender, education level, job role, and years of experience. We worked with a dataset comprising 6704 entries and 6 attributes to train and evaluate our model.

## Data Preprocessing

### Handling Missing Data
We began by inspecting the dataset for missing values. Any rows containing incomplete information were removed to ensure the model was trained on clean, reliable data.

## Data Visualization


### Top 10 Highest Paying Jobs
<img width="2400" height="1600" alt="Image" src="https://github.com/user-attachments/assets/926c4db8-04b5-4e69-b4fd-8b48f755db32" />
*A Bar plot depicting the highest paying job titles versus the mean salary.*

### Distribution of Continuous Variables
![Image](https://github.com/user-attachments/assets/e7c2856a-97cd-40d2-ad78-d9b2a5a002d0)
*This histogram shows the distribution of continuous variables in the dataset.*

### Education and Gender Level Breakdown
<img width="2800" height="1000" alt="Image" src="https://github.com/user-attachments/assets/8b663241-080f-4b59-8054-b37e2d2f5d97" />
*A plot displaying the Education Level and Gender.*

### Correlation Heatmap
<img width="1600" height="1400" alt="Image" src="https://github.com/user-attachments/assets/2e0699f4-55df-4c67-a4a2-25ae46b44536" />
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
<img width="2000" height="1200" alt="Image" src="https://github.com/user-attachments/assets/44a93742-c05a-4036-9f09-a07a24b4b632" />
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

