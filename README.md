# Insurance Prediction
The project helps improve cash flow forecasting for an insurance company by integrating demographic and basic patient health risk variables at the time of hospitalisation to better estimate patient charges and builds a web application where details are entered to predict charges.

Training and model validation are done in the Jupyter Notebook. PyCaret is used to build a machine learning pipeline and train regression models in this project. Dataset imported from Kaggle named as Medical Cost Personal Dataset.

Firstly, the dataset is imported and processed using default preprocessing settings in Pycaret that involves missing value imputation, categorical encoding etc. Then, additional preprocessing tasks such as scaling and normalization, automatic feature engineering and binning continuous data into intervals applied. 

## Methodology
<img src="https://github.com/Snehal-2310/Insurance-Bill-Prediction/blob/main/Images/Methodology.jpg" align="centre" alt="Methodolgy" width=400 height=600/> 

### Before and After Optimization

<img src="https://github.com/Snehal-2310/Insurance-Bill-Prediction/blob/main/Images/First%20approach.PNG" alt="Model without optimization" width=400 height=350/> <img src="https://github.com/Snehal-2310/Insurance-Bill-Prediction/blob/main/Images/Second%20Approach.PNG" alt="Model after optimization" width=400 height=350/>

R2 has increased by 10.8%.

### Residual plots before and after feature engineering

<img src="https://github.com/Snehal-2310/Insurance-Bill-Prediction/blob/main/Images/First%20plot.PNG" alt="Model without optimization" width=450 height=350/> <img src="https://github.com/Snehal-2310/Insurance-Bill-Prediction/blob/main/Images/Second%20plot.PNG" alt="Model after optimization" width=450 height=350/>

We can observe the impact of transformations and feature engineering on the heteroskedasticity of model.

## Web Application
Frontend is created using HTML and CSS and backend developed using Flask in Python and the app is deployed using Heruku.

An input form was created using a simple HTML template and a CSS style sheet. CSS describes an efficient method to keep your application's layout under control. Background colour, font size and colour, margins, positon of elements and other variables are all included in style sheets.

The Flask framework is used to create the back-end of a web application. It employs Jinja2, a templating language for creating HTML, XML, and other markup forms that are returned to the user via an HTTP request.

#### Input
<img src="https://github.com/Snehal-2310/Insurance-Bill-Prediction/blob/main/Images/Input.png" alt="Input"/> 

#### Output
<img src="https://github.com/Snehal-2310/Insurance-Bill-Prediction/blob/main/Images/Output.png" alt="Output"/>








