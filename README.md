# Data-Capstone-1-Final-Project
Final version of Kaggle Predict Future Sales repo

The repo addresses the following Kaggle Competition:
https://www.kaggle.com/c/competitive-data-science-predict-future-sales
Please download the raw data from there if you would like to run the notebook code.

For the prior submissions (unorganized data) for Springboard, please refer to the Kaggle Predict Future Sales repo:
https://github.com/huynhe/Kaggle-Predict-Future-Sales

This is a clean, organized version of the Kaggle Predict Future Sales repository.
The code here utilizes the same code, but is separated into three notebooks for organization purposes.

The unique files that can be found here are the final report and presentation slides which are intended for final submission.

The first of the three notebooks is labeled "Extract, Transform, Load.ipynb". This notebook contains all the code required 
to transform the raw data into working data to be used in exploratory data analysis.

The second of the three notebooks is labeled "Data Visualization and Inferential Statistics.ipynb". This notebook uses the 
working data to perform data visualizations and find trends. In addition, there is code used to perform inferential statistics 
necessary to construct statistfically different groups in the final training data. The Kaggle test data is also modified here
to be used in the models.

The last of the notebooks is labeled "Building the Model.ipynb". This notebook used the final training data to train and 
test the linear regression model. A total of 5 different models were made (each use different variables) and applied
to the modified test data. The associated visualizations and kaggle results can be found in the final report and presentation
slides. 

An additional notebook was created as an add-on to "Building the Model.ipynb". This notebook deviates from the previous by its
application of Pipeline and OneHotEncoder (in place of dummy variables) from sklearn.preprocessing. This model 
outperformed all the previous models exponentially (10x). I expect it to be due to the OneHotEncoder preprocessing step which 
assigned a value to all my categorical columns instead of me manually binning the values together.
