# Stock_Market_Predictor

## Table of Contents

1.	Project Description
2.	Team Members
3.	Data Sources
4.	Machine Learning Libraries
5.	Visualization Tools
6.	Databases
7.	Project Structure
8.	Setup Instructions
9.	Usage
10.	Expected Outcome
11.	Contributing
12.	License

### Project Description

This project focuses on predicting future stock values by training machine learning algorithms on historical data. The aim is to identify the best 5 stocks for a specified period, considering daily price changes and percentage fluctuations. Additionally, the project compares the prediction accuracy between Tensorflow (Keras library) and Scikit-Learn (Regression library).

### Team Members

1. Amanda Cantu
2. Jamie Hutton
3. Carlos Valenciano
4. Adam Saenz

### Data Sources

1. Yahoo Finance
2. Module 2 Dataset

### Machine Learning Libraries

1. Tensorflow: Keras library
2. Scikit-Learn: Regression Logistics library

### Visualization Tools

1. Tableau- [Dashboard](https://public.tableau.com/app/profile/carlos.valenciano/viz/Stock_Prediction_Visualizations_DB/Dashboard1 "Dashboard"), [Direction for Logistic Regression](https://public.tableau.com/app/profile/carlos.valenciano/viz/LogisticRegression0623-1223/LogisticDirection0623-1223 "Direction for Logistic Regresasion")
2. Matplotlib - Line graphs displaying predicted future values

### Database

1. PySpark (Spark SQL) for handling large-scale distributed datasets

### Project Structure

1. data: Contains datasets used in the project.
2. notebooks: Google Colab for data exploration, algorithm training, and analysis.
3. scripts: Python scripts for specific tasks.
4. visualizations: Output visualizations and graphs.

### Usage

1. Execute Python scripts in the scripts directory for specific tasks.
2. Explore visualizations in the visualizations directory.

### Expected Outcome

1. A trained algorithm capable of predicting future stock values.
2. Comparitive analysis showcasing the accuracy of Tensorflow and Scikit-Learn.
3. Comparitive visualizations aiding in understanding and decision-making.

### Conclusion

1. On the logistic regression, 'Up' is 46% and 'Down' is 51% so there was roughly 50/50 chance of META increase or decreasing.
2. Yearly change between 2022 was negative compared to 2023, where it was positive.
3. On 12/12/2023, META prediction for upcoming 3 days ($323.08, $323.6, $321.54). This is a bias account because it was only the daily data through one source, whereas if we could have done hourly data points through multiple source.

### License

This process is licensed under the MIT License.
