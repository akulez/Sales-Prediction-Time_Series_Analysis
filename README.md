# Store Sales Prediction
This project focuses on applying Time series Analysis for predicting store sales utilising modern day models including LSTM and Catboost. The project was done in several steps as follows:

1. **Data Analysis and Preprocessing**
   - In this part I have focused on conducting extensive initial analysis of the data using time series visualizations and descriptive statistics.
   - Visualisations including heatmap, boxplots, bar charts and line plots have been used to understand relationships between Sales and other variables in the dataset.
   - Initial preprocessing including handling of outliers and encoding of categorical variables in the dataset was also done in this part.

2. **Feature Engineering and Selection**
   - New Features were created which could help capture seasonality of the time series in hand.
   - Other features such as weekly avg. sales were also included to extract more info. about our features.
   - Once feature engineering was done, LASSO and Ridge regression were used to find the best features.

3. **Model Fitting and Evaluations:**
   - 2 Models were utilized to fit to the data, which include Catboost Algorithm and LSTM (Long Short Term Memory), which is a variant of RNN (Recurrent Neural Network).
   - Hyperparameter tuning using GridSearchCV was also performed for the models to find the best parameters for them.
   - The results of the 2 models were evaluated against each other, with catboost performing better achieving an R2 score of 0.97 on unseen data. 
