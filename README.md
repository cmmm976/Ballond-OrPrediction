# Ballond-OrPrediction
Predicting Ballon d'Or winner with Machine Learning

Stack : R, Python (Scikit, Seaborn, Pandas)

 * Scrapped 600 football players statistics (Goals, Assists, Red cards...) from Transfermarkt API
 * Scrapped Ballon d'Or ranking from 1995 to 2019 from Wikipedia
 * Merged and cleaned data to create the dataset
 * EDA
 * Tried predicting the 3 best scores (% of votes) 
   * Not a great success (overfitting with a MAE of 8%)
   * Probably due to the lack of data and mistakes in data augmentation method
