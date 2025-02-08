# Car Sales Project
This project is a part of Orange/digital hub big data analytics training. This project focuses on analyzing and predicting Car Purchase Amount using customer demographic and financial data. The goal is to gain insights through Exploratory Data Analysis (EDA), visualizations, and build a Linear Regression model to predict car purchase behavior.

## Table of Contents
- [Dataset](#dataset)
- [Task and Objectives](#task-and-objectives)
- [Exploratory Data Analysis (EDA) & Visualization](#exploratory-data-analysis-eda--visualization)
- [Model Training](#model-training)
- [Results and Evaluation](#results-and-evaluation)
- [Installation and Usage](#installation-and-usage)
- [Key Takeaways](#key-takeaways)
- [Contributors](#contributors)
- [License](#license)

## Dataset
### **Predictors:**
* Customer Name
* Customer Email
* Country
* Gender
* Age
* Annual Salary
* Credit Card Debt
* Net Worth

### **Target:**
* Car Purchase Amount

## Task and Objectives
**1. Data Analysis (EDA) & Visualization**
  - Analyze the distribution of Car Purchase Amount (Histogram/Box Plot)
  - Investigate relationships between Age, Annual Salary, Net Worth, and Car Purchase Amount (Scatter Plot/Line Chart)
  - Examine differences in car purchase amounts based on Gender (Bar Chart/Pie Chart)
  - Assess the impact of Country on car purchase behavior (Map Visualization/Bar Chart)
  - Analyze the correlation between Credit Card Debt and Car Purchase Amount

**2. Predictive Modeling**
  - Train a **Linear Regression** model using Age, Annual Salary, Net Worth, and Credit Card Debt as predictors
  - Evaluate performance using R² Score and Mean Squared Error (MSE)
  - Visualize regression results (Predicted vs. Actual values using a Scatter Plot)

## Exploratory Data Analysis (EDA) & Visualization
* A map visualization was created by preprocessing the Country column, extracting latitude and longitude, and mapping car purchase amounts geographically.
* Explore gender-based purchasing trends
* Compare average purchases across different countries
* Analyze correlations between income, debt, and purchase amounts

## Model Training
* Used Linear Regression for prediction
* Applied removing outliers using IQR method to improve model accuracy
* Trained and tested the model using train-test split (80-20 ratio)

## Results and Evaluation
* **Model Performance Metrics:**
  * R² Score: (value after model training)
  * MSE: (value after model training)
* The **scatter plot** shows predicted vs. actual values, indicating model effectiveness.

## Installation and Usage
### **Prerequisites:**
- Python 3.x
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `sklearn`, `folium`, `pycountry_convert`, `geopy`, `scipy`
### **Install Dependencies**
  ```
  pip install pandas numpy matplotlib seaborn sklearn folium pycountry_convert geopy scipy
  ```
### **Run the Project**
1. Load the dataset.
2. Perform EDA & Visualization.
3. Train the Linear Regression Model.
4. Evaluate model performance.

## Key Takeaways
* Age, Annual Salary, and Net Worth significantly influence Car Purchase Amount.
* Gender and Country impact purchasing behavior.
* The Linear Regression Model provided a strong predictive capability.

## Contributors

[Mohammed Hany](https://github.com/MohammedHany123/)

## License
This project is open-source under the **MIT License**.
