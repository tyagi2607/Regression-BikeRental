# Regression-BikeRental

company that rents bicycles wants to predict the expected number of rentals on a given day in the future, a regression model can predict this number

Linear regression

1. Exploratory analysis:

- Correlations between features and labels.
- Detect and fix issues in the data - missing values, error, outlier values
- new features by transfornmations or combinations - feature engineering
- normalizing numeric and encoding categorical as numeric indicators
- Questions looking at the column descriptions
- Target distribution and descriptions
- Numeric columns distribution and description
- Categorical columns bar chart
- Numeric features and correlations
- Y vs catrgorical columns box plots


2. Model the data

- X Y split
- Test Train split - cross validation preferred but dataset size matters in the decision
- Model the data
- Plot the y test with the predictions
- Error measurements 
    - MeanSquaredError MSE - smaller the better fit
    - Root Mean Square Error (RMSE): Absolute metric in the same unit as the label
    - Coefficient of Determination R^2 - higher the better - how much variance in predicted is the model able to explain
- Try other models - compare the error metrics
    - Lasso regression - predicted vs actual and three error metrics
- Select model

3. Preprocessing the data (Pipeline formation)
- Changing format of the data - Represent color as RGB
- Scaling numeric features
- One hot vectors for categorical 

4. Hyper parameter tuning 
- example learning rate
- Gridsearch cv within the pipeline

5. Export trained model.

6. Load model and use to predict

7. 

