# Capital Bikeshare Predictive Modeling and Optimization

## Project Description:

This project focuses on exploring relationships among selected weather features and target variables (pu_ct and do_ct) from preprocessed data. The analysis involves exploratory data analysis, building linear regression models, evaluating model performance, and making recommendations based on the findings.

## Steps:

1. **Exploratory Analysis:**
    - Explore relationships among weather features and target variables using visualizations like scatterplot matrix.
    
2. **Predictive Modeling:**
    - Build a series of linear regression models with increasing numbers of features.
    - Evaluate changes in training and test Mean Squared Errors (MSEs) with additional features.
    - Linear regression
    - Ridge regression
    - LASSO
    - Elastic Net
    - KNN regressor
    
3. **Model Selection:**
    - Determine the best linear regression models for predicting pu_ct and do_ct.
    
4. **Demonstration:**
    - Illustrate the computation of predicted pu_ct and do_ct using the chosen models.
    - Discuss optimal bike and dock allocation using the predicted values.
    
5. **Performance Evaluation:**
    - Evaluate prediction and decision performance.
    - Report findings, recommendations, and limitations.

## Components:

- Exploratory analysis
- Predictive modeling (Linear regression, Ridge regression, LASSO, Elastic Net, KNN regressor)
- Performance evaluation
- Conclusion
- Appendix (other figures, code, and output)

## Appendix:

- Cross-validation
- Comparison of model performances
- Hyperparameter tuning
- Train a final model
- Report final performance using the test data
- Comparison of model performance
- Discussion on prediction + decision strategy and its impact on business metrics
- Analysis on whether the most accurate ML model is the best for decision-making

## Steps for Decision Strategy:

1. Predict # pickups and # drop-offs (y_pred) for each test data.
2. Allocate # of bikes and # of open docks to optimize the business metric of unsuccessful pickups and unsuccessful drop-offs (based on y_pred).
3. Calculate the realized business metric based on the actual # pickups and # drop-offs (based on y_test).

![image](https://github.com/zaheersoleh/CapitalBikesharePredictiveModeling/assets/59053707/e9ef3cf5-303f-4284-952b-a07fcbb72749)

## Conclusion:

The project aims to provide insights into the relationship between weather features and bike rental demand, along with predictive models to assist in decision-making for bike allocation. It highlights the importance of considering various models and their impact on decision strategies.

For any queries or suggestions, feel free to reach out to the authors. 

*Note: Please refer to the report for detailed analysis and findings.*
