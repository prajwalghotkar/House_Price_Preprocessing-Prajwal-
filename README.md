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
