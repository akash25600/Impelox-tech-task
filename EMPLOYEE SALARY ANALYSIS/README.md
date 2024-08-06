# Impelox-tech-task

**Task 1**

**Employee-Salary-Prediction**

**🎯 Objective:**

Build a machine learning model to predict employee base salaries using the provided dataset. The goal is to perform data exploration, preprocessing, feature engineering, model building, and evaluation.

**🛠️ Built With:**

**Pandas** - Data manipulation and analysis - **import pandas as pd**

**Scikit-learn** - Machine learning library  

**matplotlib, seaborn** - Data visualization - **import matplotlib.pyplot as plt, import seaborn as sns**

**📊 Data Exploration:**

Gain insights into the dataset by performing,

**Statistical Analysis:**   Uncover key features through univariate, bivariate, and multivariate analysis.

**Univariate analysis:**

**Histogram:**   Understand the distribution of each variable and identify if they are normally distributed.

![image](https://github.com/user-attachments/assets/874ca808-ce10-4f93-8519-34beede2b6bd)


**Boxplot:**     Detect outliers in columns such as Base_Salary, Overtime_Pay, and Longevity_Pay.

![image](https://github.com/user-attachments/assets/0b489a58-2f8a-488d-8a2a-ea2ad4889a7f)

**Multivariate analysis:**    Average base_salary by gender.

![image](https://github.com/user-attachments/assets/bd442945-04e9-4b2e-b29f-c21d9ead4b40)


**Heatmap:**     Measure the strength of relationships between variables, highlighting highly correlated features like Division and Department.

![image](https://github.com/user-attachments/assets/c926bafa-12a5-4c1b-b190-32e843d3af73)





**🛠️ Data Preprocessing:**

Prepare the dataset for model training using the following steps,

**Handling Missing Values:**   Utilize pandas' fillna method to fill missing values.

**Addressing Outliers:**    Apply capping methods to correct outlier values.

![image](https://github.com/user-attachments/assets/9ec623b9-b3c4-420c-ba0f-34b510ed3853)


**Encoding Categorical Variables:**  Convert categorical values to numerical format using sklearn's LabelEncoder.

**Data Splitting:**    Split the dataset into training and testing sets with sklearn's train_test_split.

**🔍 Feature Engineering:**

Engineer features to enhance model performance, focusing on [Base_Salary] and other relevant features, for improve our model performance.

**🧩 Model Building:**

Experiment with various machine learning algorithms to identify the best-performing model,

**Linear Regression:**   Achieved the highest accuracy with sklearn's LinearRegression.

MSE: 0.0095,

R²: 0.9999

**Decision Tree:**   Implemented using sklearn's DecisionTreeRegressor.

MSE: 6350.4278,

R²: 0.6236

**Random Forest:**   Applied using sklearn's RandomForestRegressor.

MSE: 2621.7932,

R²: 0.8446

**Gradient Boosting:**   Utilized sklearn's GradientBoostingRegressor.

MSE: 1234.7530,

R²: 0.9268

Linear regression got accuracy compared to other model perfomance.

**All models:**

![image](https://github.com/user-attachments/assets/e831aeeb-173c-40ae-928a-06b90ae211d7)

**Feedback:**

if you have any queries, please feel free to ask paramanakash88@gmail.com


--------------------------------------------------------------------------------------TASK 1-------------------------------------------------------------


