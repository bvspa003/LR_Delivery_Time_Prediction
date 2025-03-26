# Delivery Time Prediction using Linear Regression

## Project Overview
This project aims to build a regression model that predicts delivery time for orders placed through Porter. The model uses various features such as items ordered, restaurant location, order protocol, and delivery partner availability to optimize operational efficiency.

## Dataset Description
The dataset contains information about orders with the following key features:
- Market ID
- Order timestamps
- Store category
- Order protocol
- Order details (items, price)
- Delivery partner information
- Distance

## Key Features
- Total items ordered
- Subtotal amount
- Number of distinct items
- Item prices (min/max)
- Delivery partner availability
- Outstanding orders
- Distance

## Methodology
1. **Data Preprocessing**
   - Feature engineering
   - Handling categorical variables
   - Outlier detection and treatment

2. **Exploratory Data Analysis**
   - Feature distributions
   - Correlation analysis
   - Target variable analysis

3. **Model Building**
   - Feature scaling
   - Linear regression implementation
   - Recursive Feature Elimination (RFE)

4. **Model Evaluation**
   - Residual analysis
   - Coefficient interpretation
   - Performance metrics

## Key Findings
- Distance and system load (outstanding orders) significantly impact delivery time
- Dasher availability shows strong inverse relationship with delivery duration
- Weekend orders typically take longer than weekday orders

## Requirements
- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
