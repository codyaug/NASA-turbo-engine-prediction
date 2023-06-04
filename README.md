# NASA-turbo-engine-prediction
Predictive Maintenance Project
This project aims to develop a predictive maintenance solution using machine learning techniques. The goal is to predict the failure of certain components in advance, enabling proactive maintenance and minimizing downtime.


1. Data Loading and Preprocessing
Loaded the dataset from the file train_FD001.txt into a pandas DataFrame.
Checked for unused columns and dropped them if necessary.
Renamed the columns to meaningful names for better understanding.
Explored the dataset by examining its shape, columns, and the head of the data.
Conducted descriptive statistics to gain insights into the data distribution and summary statistics.
Checked for missing values and handled them if present.
2. Exploratory Data Analysis (EDA)
Visualized the distribution of the 'cycle' variable using a histogram to understand the data pattern.
Created a correlation heatmap to identify relationships between different features and target variable.
3. Feature Engineering
Engineered new features based on domain knowledge to enhance predictive power.
Calculated the remaining cycles of each unit.
Ranked the remaining cycles of each unit to create the "rul" (remaining useful life) feature.
4. Data Split and Scaling
Split the dataset into train and test sets using an 80:20 ratio.
Performed feature scaling using StandardScaler to standardize the input features.
5. Model Training and Evaluation
Trained and evaluated multiple machine learning models:
Logistic Regression
Decision Tree
Random Forest
Neural Network (using Keras)
6. Model Comparison and Visualization
Compared the performance of the trained models in terms of accuracy and precision.
Created bar plots to visualize the model comparison results, emphasizing accuracy and precision scores.
7. Conclusion
In this project, I leveraged various data science techniques to develop a predictive maintenance solution. The process involved data loading and preprocessing, exploratory data analysis, feature engineering, data split, model training, and evaluation. The models were compared and visualized to identify the best-performing model for predicting component failures.

