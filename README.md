# Project Title: Analyzing IKEA Expansion Opportunities in Sweden and Predicting Electricity Prices

## Project Description:
This project aims to provide valuable insights and recommendations for IKEA's expansion strategy in Sweden and to predict electricity prices based on consumption data. The project is divided into two main tasks: Descriptive Analysis and Unsupervised Learning for identifying potential locations for IKEA stores, and Predictive Analysis and Supervised Learning for forecasting electricity prices.

### Task 1: Descriptive Analysis, Unsupervised Learning - IKEA Case
In this task, we analyze essential features of Sweden's municipalities to identify suitable locations for IKEA department stores. By applying the k-means clustering method, we discover new places in Sweden that exhibit similar properties to the municipalities where IKEA stores are already present. The clusters obtained will be evaluated, and the most promising municipalities for IKEA expansion will be determined. Visualizations will help in understanding the clusters and the distribution of data, enabling us to provide actionable insights and recommendations for IKEA's expansion strategy.

### Task 2: Predictive Analysis, Supervised Learning - Electricity Price Prediction
The second task focuses on predicting electricity prices based on consumption data. Through exploratory data analysis, preprocessing, and feature transformation, we handle missing values, convert categorical features into numeric, and discrete features into binary. We implement a Decision Tree Classifier and a Support Vector Machine to forecast the daily price of electricity. The performance of the classifiers is compared using metrics such as accuracy, precision, recall, and F1 score. Feature importance analysis is conducted to determine the significant factors influencing electricity prices. Actionable insights and recommendations for businesses are provided based on the findings.

## Project Structure:
The project repository is structured as follows:

- `README.md`: Overview of the project, objectives, and instructions.
- `data` folder: Contains the data files required for analysis (ikea_kommun_data.txt, electricitydata.csv).
- `notebooks` folder: Contains Jupyter notebooks for each task, detailing the data exploration, analysis, and implementation of machine learning algorithms.
- `results` folder: Contains visualizations and evaluation results.
- `requirements.txt`: Dependencies required to run the project.

## Getting Started:
To reproduce the project results and analyses, please follow these steps:

1. Clone the project repository: 
   ```
   git clone <repository-url>
   ```
2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```
3. Navigate to the `notebooks` folder and open the respective Jupyter notebooks for Task 1 and Task 2.
4. Execute the cells in the notebooks sequentially to perform data exploration, analysis, and model implementation.
5. Refer to the notebooks and the corresponding comments for detailed explanations of each step.
6. The visualizations and evaluation results can be found in the `results` folder.

Note: Make sure to place the data files (`ikea_kommun_data.txt`, `electricitydata.csv`) in the `data` folder before running the notebooks.

## Conclusion:
Through this project, we aim to provide valuable insights into potential expansion opportunities for IKEA in Sweden and facilitate the prediction of electricity prices based on consumption data. The analysis and predictions obtained can assist IKEA in making informed decisions regarding their expansion strategy and enable businesses to anticipate and plan for electricity expenses effectively.