# UCL-ELEC0054





External package

| Name              | Version |
| ----------------- | ------- |
| pandas            | 1.3.5   |
| numpy             | 1.21.5  |
| Nordpool          | 0.3.2   |
| pandas_datareader | 0.10.0  |
| matplotlib        | 3.5.0   |
| seaborn           | 0.11.2  |
| sklearn-learn     | 1.0.2   |
| fbprophet         | 0.7.1   |
| neuralprophet     | 0.3.2   |

### **Purpose**

Forecasting Swedish power prices, through training prices from 01/01/2019 to28/02/2022 , to predict prices from 30/04/2019 to 01/03/2022 .

### **file**

**1.Data Collection.ipynb**

collect data through API, or transform data into tidy form

**2.Data preparation.ipynb**

preprocess data including interpolation, process missing values  and outliers,then consolidate the data into a single datatable

**3.Data Exploration.ipynb**

analysis data including data relationships (covariance,correlation, autocorrelation),EDA, 

**4.forecasting-linear regression.ipynb**

train model and forecast using linear regression

**4.forecasting-knn.ipynb**

train model and forecast using KNN

**4.forecasting-DT.ipynb**

train model and forecast using Desicion Tree

**4.forecasting-prophet.ipynb**

train model and forecast using Prophet

**4.forecasting-NeuralProphet.ipynb**

train model and forecast using NeuralProphet

**4.forecasting-otherMLmodels.ipynb**

train model and forecast using some potential ML Model

**Draft-XXXX**

some attempts throughout the project

### **folder**

**data**

the location of original data and process data

**figure**

the location of saving figures
