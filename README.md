# Insurance Prediction
The project helps improve cash flow forecasting for an insurance company by integrating demographic and basic patient health risk variables at the time of hospitalisation to better estimate patient charges and builds a web application where details are entered to predict charges.

Training and model validation are done in the Jupyter Notebook. PyCaret is used to build a machine learning pipeline and train regression models in this project. Dataset imported from Kaggle named as Medical Cost Personal Dataset.

Firstly, the dataset is imported and processed using default preprocessing settings in Pycaret that involves missing value imputation, categorical encoding etc. Then, additional preprocessing tasks such as scaling and normalization, automatic feature engineering and binning continuous data into intervals applied. 

### Before and After Optimization

<img src="https://github.com/Snehal-2310/Insurance-Bill-Prediction/blob/main/Images/First%20approach.PNG" alt="Model without optimization" width=450 height=350/> <img src="https://github.com/Snehal-2310/Insurance-Bill-Prediction/blob/main/Images/Second%20Approach.PNG" alt="Model after optimization" width=450 height=350/>

R2 has increased by 10.8%.



