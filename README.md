# Employees-Burnout-Prediction
### Overview
The project focuses on predicting employee burnout using regression techniques. The goal is to identify employees at risk of burnout by analyzing various factors.
### What is Employee Burnout? 
  ### Defining Burnout :- 
          Employee burnout is a state of physical, emotional, and mental exhaustion caused by prolonged stress. It leads to decreased productivity, poor job performance, and negative impacts on health and well-being.

 ### Why is it Important?
        Burnout affects not only individual employees but also the overall efficiency and atmosphere of the workplace. Addressing burnout is crucial for maintaining a productive and healthy workforce.

# Dataset Overview
   ## Dataset Description :-
   The "Are Your Employees Burning Out?" dataset includes 22,750 entries and 9 features.
### Dataset Features
1. **Employee ID**: Unique identifier for each employee.
2. **Date of Joining**: When the employee joined the organization.
3. **Gender**: Gender of the employee (Male/Female).
4. **Company Type**: Type of company (Service/Product).
5. **WFH Setup Available**: Availability of work-from-home facility (Yes/No).
6. **Designation**: Employee's designation (0.0 to 5.0, higher is better).
7. **Resource Allocation**: Amount of resources allocated (1.0 to 10.0, higher means more).
8. **Mental Fatigue Score**: Mental fatigue level (0.0 to 10.0, where 10.0 is highest).
9. **Burn Rate**: Target variable indicating burnout rate (0.0 to 1.0).

    # Libraries Used
     1.Pandas:- Data manipulation and analysis
   
     2.NumPy :- NumPy Numerical operations
   
     3.Matplotlib & Seaborn :- Data visualization
   
     4.Scikit-learn :- Machine learning and model evaluation 

### Steps to Approach the Project

1. **Data Preprocessing**:
   - **Handle Missing Values**: Address any missing values.
   - **Convert Categorical Variables**: Use one-hot encoding for categorical variables.
   - **Feature Scaling**: Normalize or standardize features as needed.

2. **Exploratory Data Analysis (EDA)**:
   - **Understand Distributions**: Analyze distributions of features and target variables.
   - **Correlation Analysis**: Examine relationships between features and the target variable.
   - **Visualizations**: Use visualizations to identify patterns and outliers.

3. **Feature Engineering**:
   - **Create New Features**: Develop additional features if relevant (e.g., tenure-based features).
   - **Feature Selection**: Identify and select the most impactful features.

4. **Model Building**:
   - **Split Data**: Divide data into training and testing sets.
   - **Choose Regression Techniques**: Apply various regression methods like Linear Regression.
   - **Train Models**: Train models on the training set and evaluate performance using metrics like RMSE and R-squared.

5. **Model Evaluation**:
   - **Cross-Validation**: Implement cross-validation to ensure robustness.
   - **Hyperparameter Tuning**: Optimize hyperparameters for better performance.

6. **Model Interpretation and Deployment**:
   - **Interpret Results**: Analyze predictions and feature importance.
   - **Integration**: Integrate the model into HR systems if applicable.

7. **Documentation and Reporting**:
   - **Report Findings**: Document the process, results, and recommendations.
   - **Present Results**: Create a presentation or report for stakeholders.
  
     # Final Result

 Linear Regression Model Performance Metrics:

Mean Squared Error: 0.0031569779113610717

Root Mean Squared Error: 0.0561869905882231

Mean Absolute Error: 0.04595032032644773

R-squared Score: 0.918822674247248

Based on the evaluation metrics, the Linear Regression model appears to be the best model for predicting burnout analysis.

It has the lowest mean squared error, root mean squared error, and mean absolute error, indicating better accuracy and precision in its predictions. Additionally, it has the highest R-squared score, indicating a good fit to the data and explaining a higher proportion of the variance in the target variable.

So we are choosing this model for deployment.

# Future Work
Future work in employee burnout prediction includes enhancing models with advanced algorithms and interpretability techniques, integrating diverse data sources, ensuring robust data privacy, and developing systems for real-time monitoring and intervention. This will make our predictions faster although it doesn't seem to be a problem in this case.

Other things to prove is trying other linear models and more complex ones, although the relationship within the input features and target is very linear. For this, we could try:

Multivariate Adaptive Regression Splines
Deep Neural Network
KNN Regressor
Decision Tree Regressor
Random Forest Regressor
Gradient Boosting Regressor

# Conclusion
In this project, which was part ofDomain AI&ML the final project for the course Supervised Machine Learning: Regression from the IBM Machine Learning Professional Certificate, we created a python notebook to predict employee burnout using burn rate regression and EDA. The features we used included mental fatigue score, work from home status, and workload. To prepare the data for analysis, we treated null values and encoded categorical variables. We also studied correlations and applied techniques such as grid search cross validation to the data. We then used the R2 metric to evaluate the performance of our model. Overall, the goal of this project was to build a model that could accurately predict burnout risk and potentially be used by organizations to prevent burnout and promote the well-being of their employees.
      
