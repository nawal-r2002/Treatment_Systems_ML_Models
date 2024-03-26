# TreatmentSystemSpring2024

The Insulin Model was created using Jupyter Notebooks with Python

Libraries that Should Be Used: Pandas, Numpy, Scikit-Learn, Matplotlib
[Might need to download Seaborn but might not be necessary (will verify later if we need it)]
Also might need to install conda if you do not have python installed on your computer to get access to libraries

Code Breakdown:
Data Cleaning: Utilize Pandas to remove data entries that are not relevant to the data analysis and training stages of the model with the database 
(Source: https://www.kaggle.com/datasets/mathchi/diabetes-data-set)

Code Resources: 
 
1. Linear Regression Model (1 Independent Variable): https://github.com/madhurimarawat/Machine-Learning-Projects-In-Python/blob/main/Linear%20Regression%20Salary%20Prediction/ML_Linear-Regression.ipynb
2. Multiple Linear Regression Model 1: https://github.com/tanvi1911/Multiple_Regression_Analysis_on_Diabetes_Dataset
3. Multiple Linear Regression Model 2: https://github.com/sdrangan/introml/blob/master/unit03_mult_lin_reg/demo1_glucose.ipynb [I think his is the tmost applicable source for completing the project]

Important Factors to Consider as Independent Variables: Pregnancies, Glucose, Blood Pressure, Skin Thickness, BMI, Diabetes Pedigree Function, Age (Verify if this is accurate)

Dependent Variable (Output): Insulin

Machine Learning Implementation: Utilize Numpy and Scikit-Learn to create a linear regression model that 

If There is a Need to Create Analytical Plots, then we will use Matplotlib

To-Do:
[X] - Complete the Data Cleaning Process by removing irrelevant columns from the dataset
[X] - Add Data to Set Up Model for Training
[] - Complete the Pre-Processing Step for Training Model
[] - Complete the Regression Model
[] - Add Model Visuals and Complete Data Analysis