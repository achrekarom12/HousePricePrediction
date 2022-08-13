<h1>House Price Prediction using Linear Regression</h1>
<h2>Domain: Data Analysis & Machine Learning</h2>
This project was basically started as a stepping stone for learning supervised machine learning. But it turned out to be a full fledged Data Analysis & Machine learning project. <br>
Channel I followed: <a href="https://www.youtube.com/c/codebasics">Codebasics</a><br>
Dataset I used: <a href="https://www.youtube.com/c/codebasics](https://www.kaggle.com/datasets/amitabhajoy/bengaluru-house-price-data">Bengaluru House price data</a><br><br>
<b>Problem Statement: </b> Predicting house price in Bengaluru city from the data provided in CSV file. At the end predicting the efficiency score for different regression technniques and choosing the best one. 
<br><br>
<b>Steps I followed:</b>
<ol>
  <li> Importing Libraries </li>
  <li> Data Preprocessing & Cleaning </li>
  <li> Outlier Detection </li>
  <li> Creating LinearRegression Model </li>
  <li> Comparative Study of various other models </li>
</ol>
Linear regression analysis is used to predict the value of a variable based on the value of another variable. The variable you want to predict is called the dependent variable. The variable you are using to predict the other variable's value is called the independent variable.<br>
Here in this notebook we are going to predict the prices of house based on the data we have.
<br><br>
Data Frames I created:<br>
df -> Original dataframe in which we loaded our csv file<br>
df_revised -> Dropped 'area_type', 'availability', 'society', 'balcony'<br>
df_without_null -> Removed all null values<br>
df_without_size -> Dropped redundant size column and values of that column stored into new column named 'flat_size'<br>
df_sqft_normalised -> Normalised total_sqft column removed the ranges<br>
df_including_price_per_sqft -> Inserted a new column in which the value per sqft is mentioned.<br>
df_cleaned_1 -> After resolving anomaly 1<br>
df_cleaned_2 -> After resolving anomaly 2<br>
df_cleaned_3 -> After resolving anomaly 3<br>
df_cleaned_4 -> After resolving anomaly 4<br>
df_for_model -> Final dataframe which will be used for training the model<br>
dummies_for_model -> Dummy variables for location<br>
df_for_model_2 -> Concatenation between dummies_for_model & df_for_model<br>
df_for_model_3 -> Dropped location column because we already have one hot encoding<br>
<br>

<b>Concept that got covered in this project:</b><br>
<ol>
  <li> Data Preprocessing & Cleaning </li>
  <li> Dimensionality Curse problem </li>
  <li> Outlier Detection </li>
  <li> One hot encoding </li>
  <li> Dummy Variables & Dummy variable trap</li>
  <li> K-fold Corss validation </li>
  <li> Comparative analysis between different regression models </li>
</ol>


<b>References:</b><br>
<ol>
  <li> [Data Preprocessing & Cleaning](https://www.youtube.com/watch?v=x08AN87G0mg) </li>
  <li> [Dimensionality Curse problem ](https://www.youtube.com/watch?v=QZ0DtNFdDko)</li>
  <li> [Outlier Analysis](https://www.youtube.com/watch?v=7sJaRHF03K8) </li>
  <li> [One hot encoding](https://youtu.be/9yl6-HEY7_s) </li>
  <li> [K-fold Corss validation](https://youtu.be/gJo0uNL-5Qw) </li>
  <li> [Different regression models ](https://youtu.be/E5RjzSK0fvY)</li>
</ol>

<br><b>Future Scope:</b>
Implementing the house price prediction using different regression techniques and analyze them.
<a href="https://www.kaggle.com/code/emrearslan123/house-price-prediction">Refer this in future!</a>








