# House_Price Preprocessing (Prajwal) 

# Pre-Processing Steps:

#### 1) Import relevant libraries
#### 2) Import thye Data Set to analyse and clean for prediction
#### 3) Missing value treatment(Impute the dataset)
##### * In numerical data
###### * Populate with mean - When there is no outlier
###### * Populate with median - When there is outlier
#### 4) Categorical data - Model imputation - Maximum data category
#### 5) Encoding
##### * Label Encoding - Convert to number
##### * One Hot Encoding - Create multiple columns based on number of unique record count.
#### 6) Feature Scaling
##### * Standardization - When there no outlier.
##### * Normalization/ MIn Max Scaler : When there is outlier.

## Standardization:

Xnew = Xi - Xmean / Standard Deviation

## Min Max Scaler:

Z = X - min(x) / [max(x) - min(x)]


#### Univariate Analysis
###### * The term univariate analysis refers to the analysis of one variable. You can remeber this because the prefix 'uni' means 'one'.
###### * The univeriate analysis aims to understand the distribution of values for a single variable.

###### * Bivariate Analysis : The analysis of two variables.
###### * Multivariate Analysis : The analysis of two or more variables.

#### Examples of Univariate Analysis
##### Central Tendency
###### * Mean
###### * Mode
###### * Median

##### Dispersion
###### * Range
###### * Variance
###### * Maximum,Minimum
###### * Quartiles
###### * Stanadard Deviation

##### Count / Null Count
###### Charts
###### * BoxPlot
###### * Histogram
###### * Density Curve
###### * Pie Chart

##### Do the Analysis of
###### * Missing Values in - n_hos_beds
###### * Skewness or Outliers in crime_rate
###### * Outliers in n_hot_rooms and rainfall
###### * Bus-ter taking only Yes

#### Outekier Treatment
##### Outlier is an observation that appears far away and diverges from an over all pattern in a sample.

#### Reason
##### * Data Entry Errors
##### * Measurement Erro
##### * Sampling Error

#### Impact
##### * In increases the error variance and reduces the power of statistical tests

#### Solution
##### * Detect outliers using EDD and visualization methods such as scatter plots,histograms or box plots
##### * Impute outliers Data Entry Error

#### Fix the Outlier (Capping and Flooring)
##### * Impute all values above 3* Percentile 99 and below 0.3 * Percentile 1
##### * Impute with values 3 * Percentile 99 and 0.3 * Percentile 1
##### * You can use any multiplier instead of 3

🙋‍♂️ 👨‍💻 Developed by Prajwal Ghotkar 

