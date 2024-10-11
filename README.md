# California House-Price-Prediction

 Run in google Colab.
 Utilised SkLearn to fetch california housing dataset. The dataset was converted into a dataframe using pandas for preprocessing.
 Correlation was established using heatmap from seaborn and plotted using matplotlib module.
 Training was done on XGBoost Regressor Model- Its a decision tree based ensemble model. Ensemble meaning more than 1 model is used together. Used this model since the dataset isn't too big (20640, 9).
 80% of the data was used for training and 20% for testing with test prediction resulting at 83% while training resulted in 94% correct prediction.
 Since it's a regression problem the evaluation metrics used were r squared and mean absolute error.
