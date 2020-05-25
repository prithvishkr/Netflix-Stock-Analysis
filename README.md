# Netflix-Stock-Analysis
Exploratory Data Analysis Of Netflix Stock and Prediction 

## Insights

1) Check for null values if there are any then replace them with required values. We can use mean

2) Plot all values individually with date

   Opening Value had a great increase after 2016 
  
   High, Low, Close, Adj Cose Value had a great increase after 2016
  
   The volume had the highest in year 2012
  
3) We check for correlation matrix any value which has value less than -0.5 & greater than +0.5

4) We then check for outlier values it is checked using whisker plot

5) To remove outlier values we use IQR method

6) After data is processed we check for pattern in this data 

7) We check for time series influence of total volume based on year and month

    2011 had the highest volume trade
  
## Prediction

Here we are using a python library called FbProphet. It is highly specific library for stock prediction

**Installation**

conda install -c conda-forge fbprophet

pip install fbprophet

