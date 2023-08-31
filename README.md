# Multiple Linear Regression
🛠️ Tools: Python (Google Colab Notebooks) <br>
💁 Dataset: From Kaggle, [here](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python).

## 📄 Overview
In the mall, we can see all kinds of people. Each person has their own behavior. A person's behavior is usually influenced by several factors, such as age, gender, and income. This repository will show the relationship between the existing independent variables and the dependent variable (spending score) using multiple linear regression.

## 🔍 Objective
1. Knowing the relationship between variabel independent (age, gender, and annual income) on variabel dependent (spending score)
2. Knowing prediction of dependent variable values.
   
## 🙌 Results
### 🔄️ The Relationship Between Age, Gender and Annual Income on Spending Score
From multiple linear regression, we got the following equation: <br>
<br>
$Spending Score = 75.45869711082925 + 3.96392335Gender - 0.78215421Age + 0.09941211Annual Income$ <br>
<br>
From these equations, it can be seen that: <br>
1. If a person's gender is female, it will increase the spending score by 3.96, whereas if the gender is male, it will not increase the spending score. <br>
2. As age increases, the spending score will decrease. If a person's age increases by 1 year, the spending score will decrease by 0.78. <br>
3. The greater a person's annual income, the greater the spending score. If a person's annual income increases by $1,000, it will increase the spending score by 0.099. <br>

### 🤔 Prediction of Dependent Variable Values
Apart from being able to see the relationship between the independent variable and the dependent variable, multiple linear regression can also be used to make predictions on the dependent variable. Following are the results: <br>
<p align="center">
<img width="312" alt="image" src="https://github.com/ramadhanakirana/Multiple-Linear-Regression/assets/102908444/af25a8d1-f37a-4357-ab27-ee24ef5e530e">
</p> 
<p align="center">Figure 1. Prediction of Dependent Variable Values</p>
