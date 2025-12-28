# house_price_prediction-ml-project
In this project, I applied supervised machine learning regression techniques to predict median house values in California using the California housing dataset from scikit-learn. The goal is to explore the dataset, understand key factors influencing housing prices, and compare the performance of different regression models. 

Problem Statement: I have to accurately estimate housing prices for real estate valuation, investment decision-making and urban planning and policy development. This project aims to predict median house values based on features like income levels, household characteristics , population density, and location. 

Dataset: I used the California Housing Dataset from scikit-learn. 

****EDA (Exploratory Data Analysis):**

**Key steps include:**

- Summary statistics to understand data distribution.

- Visualisation of house value distribution. 

- Scatter analysis between median income and house value, revealing a strong positive correlation. 

The EDA helped to validate feature relevance and confirms that regression is appropriate. 

**Machine Learning Pipeline:**

**Data Preparation:** 

- Feature and target separation

- Train–test split (80/20) to ensure unbiased evaluation

**Models Implemented:**

**Linear Regression:**

- Baseline model

- Assumes linear relationships

**Decision Tree Regressor:**

- Captures non-linear patterns

- Learns feature interactions automatically

**Model Evaluation:**

****Models were evaluated using:**

- Mean Absolute Error (MAE)

- R² Score

**Key Insights:**

- Median income is the strongest predictor of housing prices

- Non-linear models outperform linear models for this dataset

- Geographic features (latitude and longitude) significantly influence house value

**Future Improvements:**

- Hyperparameter tuning (GridSearchCV)

- Cross-validation

- Feature importance visualization

- Ensemble models (Random Forest, Gradient Boosting)

**Technologies used:**

- Python

- Pandas

- Numpy

- Matplotlib
  
- Seaborn

- Scikit-learn

- Jupyter Notebook
