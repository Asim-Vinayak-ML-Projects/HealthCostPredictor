# Medical Cost Prediction

## Overview
This project involves predicting the medical costs of customers based on various parameters using different regression models. The dataset used for this project is the insurance dataset from Kaggle. We evaluated multiple regression models and compared their performance based on the R² values.

## Dataset
The dataset contains the following columns:
- **age**: Age of the customer
- **sex**: Gender of the customer
- **bmi**: Body Mass Index of the customer
- **children**: Number of children the customer has
- **smoker**: Smoking status of the customer
- **region**: Region of the customer
- **charges**: Medical cost charged to the customer

## Regression Models and R² Values
We used the following regression models to predict the medical costs and calculated their R² values to evaluate their performance:
- **Multiple Linear Regression**: R² = 0.7339
- **Polynomial Regression**: R² = 0.8652
- **Decision Tree Regression**: R² = 0.6884
- **Random Forest Regression**: R² = 0.9756
- **Support Vector Regression (SVR)**: R² = 0.8365

## Results and Conclusion
The Random Forest Regression model provided the best fit for the data, achieving the highest R² value of 0.9756. This indicates that the Random Forest model is able to capture the complexity of the data and provides a more accurate prediction of medical costs compared to other models.

### Visualizations
Here are the visualizations of the actual vs. predicted medical costs for some of the models:

#### Random Forest Regression
![Random Forest Regression](https://github.com/Asim-Vinayak-ML-Projects/HealthCostPredictor/assets/140016882/5f5304f3-4da1-417b-9b96-6c2e547a9d11)

**Interpretation**: The scatter plot for the Random Forest model shows that the predicted medical costs are closely aligned with the actual costs, indicating high accuracy and good model performance. The points are distributed along the line \(y = x\), demonstrating the model's ability to predict values that are very close to the true values.

![Support Vector Regression](https://github.com/Asim-Vinayak-ML-Projects/HealthCostPredictor/assets/140016882/fc06da2b-e711-40c1-9332-3d94fbdd3fde)

**Interpretation**: The residual plot for the Random Forest model shows that the residuals are centered around zero with no clear pattern. This indicates that the model's errors are randomly distributed, suggesting that the model is a good fit for the data. The spread of residuals is relatively consistent across different test samples, demonstrating the model's ability to generalize well to unseen data.

## Conclusion
The Random Forest model outperformed the other regression models due to its ability to handle non-linear relationships and interactions between features. It combines the predictions from multiple decision trees to reduce overfitting and improve generalization. As a result, it provides the most accurate predictions for the medical costs in this dataset.

## Installation and Setup
### Prerequisites
- Python 3.x
- Jupyter Notebook

### Setup
1. Clone the repository:
   ```bash
   git clone "https://github.com/Asim-Vinayak-ML-Projects/HealthCostPredictor.git"
   cd <repository-directory>

2. Run the Jupyter Notebook::
   ```bash
   jupyter notebook

3. Open the notebook file and run the cells to see the results.:






