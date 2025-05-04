# Insurance-Cost
MGT 665 Comprehensive Exam Question 16

Summary: I chose to use a linear regression based on the insurance cost dataset from Kaggle which is found cited below. This dataset uses age, gender, where they live, body mass index, family, and if they're a smoker as the indicators to try to predict the patient's insurance cost. 

Source: https://www.kaggle.com/datasets/mirichoi0218/insurance

Steps Taken:
  Using one hot encoding to preprocess the data. Based on the data set above, there wasn't much if any cleaning to be done to have it ready for a regression model and MSE or Mean Squared Error.
  Once the preprocessing has been done, I fed the data through LinearRegression off sklearn.
  Finally, the data was measured through MSE

 MSE: 32,193,193

Reflection: 
  We used a linear regression from sklearn to predict the correlation between age, gender, where the patient lives, body mass index, family, and if they're a smoker to see how it impacts their insurance costs and measured through MSE. The dataset we used an insurance dataset from Kaggle that's linked above. First we preprocessed the data with OHE and cleaned if it was necessary, and then measured it with MSE where we got the 32,193,193. Analyzing why this value seemed so high, there was a lot of variance in this dataset. Some values were as low as a couple hundred USD, while others would 10's of thousands so it makes sense why our MSE got this high. We could improve this through some random bagging models as well. 
