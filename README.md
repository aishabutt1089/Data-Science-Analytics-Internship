# Data Science & Analytics Internship - Developers Hub Corporation

This repository contains my official task submissions for the Data Science & Analytics Internship at Developers Hub Corporation. The project focuses on data exploration, cleaning, visualization, and machine learning modeling using Python.

---

## 🛠️ Task 1: Exploring and Visualizing a Simple Dataset (Iris Dataset)

### 1. Objective
To understand how to read, inspect, and visualize a standard dataset to uncover underlying patterns and structures.

### 2. Approach
- **Data Loading:** Loaded the built-in Iris dataset using the `seaborn` library.
- **Inspection:** Explored the dataset's structural dimensions using `.shape`, `.columns`, and `.head()` methods.
- **Visualizations:** Created three distinct plots using `matplotlib` and `seaborn`:
  - **Scatter Plot:** To analyze the length and width relationships between sepals across different species.
  - **Histogram:** To examine the density distribution of petal lengths.
  - **Box Plot:** To detect outliers and identify the spread of values for petal width.

### 3. Results & Insights
- The dataset contains 150 rows and 5 columns.
- The **Iris-setosa** species is highly distinct and easily separable from *versicolor* and *virginica*, particularly when looking at petal measurements.
- Minimal outliers were detected in sepal dimensions, confirming high data quality.

---

## 💳 Task 2: Credit Risk Prediction

### 1. Objective
To build a binary classification machine learning model that predicts whether a loan applicant is likely to default on their loan.

### 2. Approach
- **Data Cleaning:** Handled missing data entries using statistical imputation (filling missing values with continuous median and categorical mode values).
- **Exploratory Data Analysis (EDA):** Visualized key applicant attributes such as education levels and loan approval distributions.
- **Data Preprocessing:** Utilized `LabelEncoder` to transform categorical text variables into numeric format.
- **Model Training:** Split data into training and validation sets, and trained a **Logistic Regression** classification model.
- **Evaluation:** Evaluated the performance using a confusion matrix heatmap and an accuracy score metric.

### 3. Results & Insights
- The model achieved a strong baseline **Accuracy of ~78.86%**.
- The confusion matrix clearly maps the true vs. predicted counts of approved and refused loans.
- **Credit History** emerged as the most critical determining feature influencing loan approval status.

---

## 🏥 Task 4: Predicting Insurance Claim Amounts

### 1. Objective
To build a predictive regression model that estimates medical insurance claim charges based on individual personal attributes.

### 2. Approach
- **Exploratory Analysis:** Created a feature correlation scatter plot to visualize how variables like Body Mass Index (BMI) and smoking habits impact insurance charges.
- **Data Preprocessing:** Mapped binary categorical variables ('smoker' status) into numeric indicator variables (1 for yes, 0 for no).
- **Model Training:** Developed and trained a **Linear Regression** model to accurately predict continuous medical cost charges.
- **Evaluation:** Analyzed model performance and prediction errors using Mean Absolute Error (**MAE**) and Root Mean Squared Error (**RMSE**).

### 3. Results & Insights
- **Smoking status** has an exceptionally high positive correlation with insurance charges, exponentially driving up medical costs.
- Higher **BMI and Age** demonstrate a steady linear growth trend regarding insurance claims.
- The **MAE** and **RMSE** evaluation metrics successfully set a clear performance benchmark for predicting data deviations.

---
*All code implementations are cleanly structured, heavily documented with descriptive English comments, and formatted perfectly inside individual Jupyter Notebooks (`.ipynb`).*
