# AI/ML Project: Housing Price Prediction 🏘️
<p align="center"><img src="https://user-images.githubusercontent.com/54996245/144111000-4a142a69-fc68-4976-895e-09effd1cb0e6.png" style="width: 1000px;"/></p>

### Description:

A simple yet challenging project, to predict the housing price based on certain factors like house area, bedrooms, furnished, nearness to mainroad, etc. The dataset is small yet, it's complexity arises due to the fact that it has strong multicollinearity. Can you overcome these obstacles & build a decent predictive model?

**Source**
Harrison, D. and Rubinfeld, D.L. (1978) Hedonic prices and the demand for clean air. J. Environ. Economics and Management 5, 81–102.
Belsley D.A., Kuh, E. and Welsch, R.E. (1980) Regression Diagnostics. Identifying Influential Data and Sources of Collinearity. New York: Wiley.


### Objective:
- Understand the Dataset & cleanup (if required).
- Build Regression models to predict the price w.r.t a single & multiple feature.
- Also evaluate the models & compare thier respective scores like R2, RMSE, etc.
- 
### <center> Stractegic Plan of Action:
  
**We aim to solve the current problem statement by creating plan of action, Here are some of the necessary steps:**
1. Data Exploration
2. Exploratory Data Analysis (EDA)
3. Data Pre-processing
4. Feature Selection/Extraction
5. Predictive Modelling
6. Project Outcomes & Conclusion

### Some Visuals of the Project:
**1. Target Variable Distribution**

<p align="left"><img src="https://user-images.githubusercontent.com/54996245/144111152-ccbf8839-2ba8-420e-80b5-af0433735c80.png" /></p>

**2. Categorical Feature-set Distribution**
  
![image](https://user-images.githubusercontent.com/54996245/144111173-740b7634-a2dc-48bd-9e4b-21e7b0d488c2.png)

**3. Numerical Feature-set Distribution**

![image](https://user-images.githubusercontent.com/54996245/144111216-09504767-67f1-40ee-8193-58410dcda662.png)
![image](https://user-images.githubusercontent.com/54996245/144111237-50a6362d-7abb-4a16-afea-606b317e329b.png)

**4. Relationship between the Feature-set**

![image](https://user-images.githubusercontent.com/54996245/144111287-c6f31324-e745-45e8-85c1-0b848e39618a.png)

**5. Data Retention after preforming preprocessing step**

![image](https://user-images.githubusercontent.com/54996245/144111313-5f75a994-d5af-40d8-82e7-2e077270e5a7.png)

**6. Correlation Plot**
  
![image](https://user-images.githubusercontent.com/54996245/144111340-c392e999-a8d8-44f1-9f31-c23cf389951c.png)

**7. Multiple Linear Regression Prediction & Residual Normality Check**
  
![image](https://user-images.githubusercontent.com/54996245/144111397-3b8aa41d-50bf-478d-b44c-8dd5744fec7c.png)

**8. Polynomial Degrees Comparison**

![image](https://user-images.githubusercontent.com/54996245/144111455-2eb0f410-6301-41be-bac6-a34fa00da180.png)

**9. Predictions**

![image](https://user-images.githubusercontent.com/54996245/142776716-722f804a-6b40-4ebe-99a7-0b8cef3989ae.png)


**10. ML Algorithm's Scores Comparison (R2& RMSE) for the Ad Budge Dataset**

![image](https://user-images.githubusercontent.com/54996245/144111498-e8619d77-adba-4f6e-8885-421637083abe.png)
![image](https://user-images.githubusercontent.com/54996245/144111535-e9e5c3fd-b9a5-4756-ba0e-3b0be00eaa88.png)


### Here are some of the key outcomes of the project:
- The Dataset was quiet small totally just 545 samples & after preprocessing 2.2% of the datasamples were dropped. 
- Visualising the distribution of data & their relationships, helped us to get some insights on the feature-set.
- The features had high multicollinearity, hence in Feature Extraction step, we used VIF & RFE Techniques to drop highly correlated features.
- Testing multiple algorithms with default hyperparamters gave us some understanding for various models performance on this specific dataset.
- While, Polynomial Regression (Order-5) was slightly overfitting, it is safe to use multiple regression algorithm, as their scores were quiet comparable & also they're more generalisable.
