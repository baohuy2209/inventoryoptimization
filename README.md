# Medical Inventory Optimization

Welcome to the Medical Inventory Optimization Project on GitHub. This project is designed to optimize medical inventory management within healthcare institutions by leveraging data-driven insights and advanced forecasting techniques. It integrates data analytics, statistical modeling, and optimization strategies to enhance efficiency, reduce costs, and ensure optimal stock availability of essential medical supplies.

![image](https://github.com/mukul-bhele/inventoryoptimization/blob/a4bda0fed3e0286c622b06a977f45e524fd2ec90/Medical%20Inventory%20Optimization%20(Image).jpeg)
## Table of Contents
1. [Technical Overview](#technical-overview)
2. [Business Problem and Objectives](#business-problem-and-objectives)
3. [Data Preprocessing](#data-preprocessing)
4. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
5. [Forecasting Model](#forecasting-model)
6. [Project Challenges](#project-challenges)
7. [Future Scopes](#future-scopes)
8. [License](#license)

## Technical Overview

The Medical Inventory Optimization Project is a comprehensive initiative that harnesses data analytics and forecasting techniques. It consists of the following components:

### 1. Data Collection and Analysis

We collected historical medical inventory data, including consumption patterns, order quantities, and lead times. This data was subjected to exploratory data analysis (EDA) to identify trends, seasonality, and irregularities. 

### 2. Forecasting Models

To predict future demand, we implemented a variety of forecasting models

### 3. Demand Variability Analysis

An essential part of our project involved analyzing demand variability and uncertainty. This analysis allowed us to adjust our models for potential outliers and unexpected changes.

### 4. Optimization Strategies

We developed inventory optimization strategies that determine:

- Reorder Points: The point at which orders should be placed to avoid stockouts.
- Order Quantities: The optimal quantities to order based on demand and lead times.

### 5. Performance Metrics

We evaluated our forecasting models using metrics such as Mean Absolute Error (MAE) and Mean Squared Error (MSE) to assess their accuracy.

### 6. Real-time Monitoring

The developed models and strategies were implemented in a real-time environment to monitor and validate their performance.

## Business Problem and Objectives

The primary business problem we aimed to solve with this project is the occurrence of drug shortages within healthcare institutions. Our objectives were:

- Minimize drug shortages.
- Maximize the availability of drugs to improve customer satisfaction and increase profits.

## Data Preprocessing

Our data preprocessing phase was crucial in preparing the data for analysis and modeling. It involved:

- **Data Cleaning**: Identifying and rectifying errors, inconsistencies, and missing values in the dataset.
- **Data Transformation**: Converting data into an appropriate format or scale for analysis or modeling.
- **Feature Engineering**: Creating new relevant features or variables from the existing data to improve the performance of machine learning models.

## Exploratory Data Analysis (EDA)

After data preprocessing, we conducted an extensive EDA to analyze the trends and patterns within the datasets. Our EDA included:

- Data Distribution Analysis: Understanding the distribution of data and identifying any skewness.
- Data Transformation: Log transformation to normalize data distributions.
- Histograms and Bar Plots: Visualizing quantities of drugs sold by month and identifying trends.
- AutoEDA using D-Tale: An automated EDA tool to provide in-depth insights into the data.

## Forecasting Model

The heart of our project is the development of forecasting models to predict the demand for medical supplies. This involved the following steps:

- Model Selection: We selected and evaluated two main models, the Random Forest Regression Model and the Linear Regression Model.
- Training and Testing: We split historical data into training and testing sets, training the models on the former and assessing their performance on the latter.
- Forecast Generation: The trained models were used to generate forecasts for the required period.
- Evaluation Metrics: We used common evaluation metrics such as Mean Squared Error (MSE) and Mean Absolute Percentage Error (MAPE) to assess the accuracy of each model.

### Model Results

1. **Holt-Winters Method**:
    - MAPE: Not available
    - RMSE: 5032.71

2. **Random Forest Regression**:
    - MSE: 111.61

3. **Linear Regression**:
    - MSE: 159.58

Our evaluation indicated that the Random Forest Regression Model was the better performer in terms of prediction accuracy. This model captured complex non-linear relationships and was less sensitive to outliers, making it more reliable.

## Project Challenges

While implementing this project, we encountered several challenges, including:

- Difficulty predicting stock with return quantity.
- Privacy concerns related to patients' health condition data.
- Limited knowledge of new drug development.
- Ensuring compliance with pharmaceutical regulations and patient privacy laws.
- Complex data integration with existing inventory systems.
- External factors such as market shifts and unexpected events impacting the accuracy of forecasting models.

## Future Scopes

Looking ahead, there are several exciting opportunities for this project:

1. **Enhanced Forecasting Model**: Continuously improving and refining the pharmaceutical forecasting model by incorporating more advanced machine learning techniques, considering additional factors like seasonal trends, public health events, and external influences on medicine demand.

2. **Supply Chain Optimization**: Collaborating with suppliers and distributors to optimize the entire supply chain. This might involve streamlining delivery routes and reducing lead times.

3. **Machine Learning for Bounce Rate Reduction**: Utilizing machine learning to predict and mitigate factors causing high bounce rates in pharmacies, offering insights into optimizing store layouts and reducing return products.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Thank you for exploring the Medical Inventory Optimization Project on GitHub. Your contributions, feedback, and collaborations are highly valued. If you have any questions or would like to get involved, please reach out to me.
