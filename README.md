# HDDFailure

We need to predict if a hard drive is going to fail in the next 'N' days('N' is optimal value). If we can predict failure before 'N' days, we get sufficient time to retrieve the data and can replace that with a new drive. Using the data provided by Backblaze, we apply different machine learning algorithms to predict the failures.

**Files Uploaded:**

Exploratory_Data_Analysis_&_Preprocessing.ipynb - This file consists of code for EDA and Pre-processing

Feature_Engineering_&_Modelling.ipynb - This file has complete code for extracting time series features and data modelling

Final.ipynb - It has two functions

**Function-1:**<br />
Includes entire pipeline, from data preprocessing to making final predictions.<br />
Takes in raw data as input.<br />
Returns predictions for the input.

**Function-2:**<br />
Includes entire pipeline, from data preprocessing to making final predictions.<br />
Take in raw data as input along with its target values.<br />
Returns the metric value.
