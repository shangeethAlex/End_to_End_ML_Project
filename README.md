# End-to-End ML Project: Student Performance Indicator 🌟

### Problem Statement
We sought to explore the impact of different variables on students' test scores. Our dataset comprised 8 columns and 1000 rows, providing a solid foundation for our analysis.

### Project Phases
##### Exploratory Data Analysis (EDA): Delved into the dataset to uncover patterns, relationships, and insights. This step was crucial in shaping our approach and identifying key variables.

##### Data Ingestion: Systematically gathered and organized data, ensuring it was ready for transformation and analysis.

##### Data Transformation: Processed the raw data into a format suitable for model training, addressing missing values, encoding categorical variables, and normalizing numerical features.

##### Model Training: Incorporated a variety of regression models including:

######  -> RandomForestRegressor
###### -> DecisionTreeRegressor
###### -> GradientBoostingRegressor
###### -> LinearRegression
###### -> XGBRegressor
###### -> CatBoostRegressor
###### -> AdaBoostRegressor

Each model underwent hyperparameter tuning through a custom evaluation function to ensure optimal performance.

##### Model Evaluation: Assessed each model using the R² score on both training and testing datasets. The best-performing model was selected based on rigorous evaluation.

##### Model Deployment: Prepared the best model for deployment, ensuring it was production-ready.

##### CI/CD Pipelines: Implemented Continuous Integration and Continuous Deployment using GitHub Actions to streamline the development process.

##### Deployment: Successfully deployed the model on AWS, making it accessible and scalable for real-world use.

This project highlights the power of a structured, end-to-end machine learning pipeline, from data ingestion to model deployment. The insights gained can significantly contribute to understanding and improving student performance.
