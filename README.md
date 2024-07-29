# Prediction of Median House Values in Californian Districts

## Project Objective

This project aims to predict the median house values in various districts of California using machine learning models. The primary objective is to explore different regression techniques and evaluate their performance on this dataset.

## Dataset Details

The dataset used for this project is the California Housing dataset. It contains information collected during the 1990 California census, including features such as:

- Longitude and Latitude: Geographical coordinates of the district.
- Housing Median Age: Median age of the houses in the district.
- Total Rooms: Total number of rooms in all houses within the district.
- Total Bedrooms: Total number of bedrooms in all houses within the district.
- Population: Total population of the district.
- Households: Total number of households in the district.
- Median Income: Median income of the district's inhabitants.
- Median House Value: Median house value in the district (target variable).

## Models and Technologies

### Models
- **Linear Regression**: A basic model to establish a baseline performance.
- **Decision Tree Regressor**: A non-linear model that splits the data into branches to improve prediction accuracy.
- **Random Forest Regressor**: An ensemble model that builds multiple decision trees and averages their predictions to reduce overfitting.
- **Gradient Boosting Regressor**: An advanced ensemble technique that builds trees sequentially to correct errors of the previous trees.

### Technologies
- **Python**: The primary programming language used for this project.
- **Jupyter Notebook**: For interactive development and visualization.
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical operations.
- **Scikit-learn**: For building and evaluating machine learning models.
- **Matplotlib and Seaborn**: For data visualization.

## Code
### Data Loading and Preprocessing
- **Loading Data**: The dataset is loaded using Pandas, and initial exploration is performed to understand the structure and missing values.
- **Data Cleaning**: Missing values are handled by filling or dropping them. Features are scaled and normalized to prepare them for modeling.
- **Feature Engineering**: New features are created to enhance the predictive power of the models.

### Model Training and Evaluation
- **Linear Regression**: The model is trained on the dataset, and performance metrics like RMSE and R² are calculated.
- **Decision Tree Regressor**: The model is trained with default and tuned hyperparameters, followed by performance evaluation.
- **Random Forest Regressor**: Similar steps are followed as in the Decision Tree Regressor, with additional averaging of multiple trees.
- **Gradient Boosting Regressor**: The model is trained with various learning rates and estimators, and its performance is compared with other models.

### Results and Analysis
- **Model Comparison**: A comparison of all models based on performance metrics and visualizations.
- **Feature Importance**: Analysis of the most significant features affecting the median house values.

### Conclusions and Future Work
- **Summary**: Summary of the findings and the best-performing model.
- **Future Work**: Suggestions for improving the model, such as using more advanced techniques or incorporating additional features.
